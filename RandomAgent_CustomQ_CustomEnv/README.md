# Custom Q_function , Not Deep With Custom Environment

<img src="https://github.com/hamidahmadian/RL-Notebook/tree/master/RandomAgent_CustomQ_CustomEnv/sample.gif" width="329" height="478">

### Q_function,Parameterized

- *we create custom Env*

- *we parameterized Q_function just with 3 params,check it in notebook*

- *we are trying to learn theta parameter with q_learning (or minimizing td loss) methods also for stabilize learning process,we use experience replay*

- *The initial point for theta is [0,0,0],plus we use torch tensor with cuda enabled ,for calculate gradient in gpu* 
