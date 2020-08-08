# RL-Notebook
# Custom Q_function , Not Deep

### Q_function,Parameterized
- *we parameterized Q_function just with 3 params,check it below*

$Q_{\theta}(dist_{AI},dist_{agent_{i}}) = \theta _{1}*dist_{AI} + \sum _{i} (e ^{\theta_{2} + \theta_{3}*dist_{agent_{i}}})$

- *we are trying to learn $\theta _{1},\theta_{2},\theta_{3}$ with q_learning (or minimizing td loss) methods also for stabilize learning process will use experience replay*

- *The initial point for $\theta$ is [0,0,0],plus we use torch tensor with cuda enabled ,for calculate gradient in gpu* 
