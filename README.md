# FetchingNAS
Use RL(ActorCritic) and Fetching method for Searching Neural Network Operations

FetchingNAS is different from other NAS models since it’s not trying to create a graph. FetchingNAS is focusing on the operations and pass more control to the Agent. Therefore, the agent can just combine multiple operations to make the model it want. The num_fetching_steps restrict the agent to return the output before the max steps. 

![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/FetchingSteps.png?raw=true)

#### Training on MNIST (for 70 epochs < Roughtly 6 hours on one GPU >):

![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/Train_Hist_Rewards.png?raw=true)


### The results show they use the same weight repetitively
#### Best Dag

![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/Best%20dags.png?raw=true)


