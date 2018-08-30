# FetchingNAS
Use RL(ActorCritic) and Fetching method for Searching Neural Network Operations

FetchingNAS is different from other NAS models since it’s not trying to create a graph. FetchingNAS is focusing on the operations and passing more right of control to the Agent. Therefore, the agent has the right to select the weights and the operation it wants.

![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/FetchingSteps.png?raw=true)

#### Training on MNIST (for 70 epochs < Roughtly 6 hours on one GPU >):

![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/Train_Hist_Rewards.png?raw=true)


### The results show they use the same weight repetitively
#### Best Dag

![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/Best%20dags.png?raw=true)


