# Bootstrapped DQN Breakout Environment

<img src="https://github.com/hamidahmadian/RL-Notebook/blob/master/Bootsrapped_DQN_Breakout/benchmark.png" width="512" height="256">

### Important Points

- implement data-dependent dropout with `nn.ModuleList` in pytorch 

- Each head was trained on its bootstrapped sub-sample of data with `BERNOULLI_P` config params

- We use exprience replay and target network that updates slower than online network to stabilize learning

- We use `retain_graph=True` to calculate gradient of each head to be trained against its own target network
