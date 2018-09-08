# FetchingNAS
Use RL(ActorCritic) and Fetching method for Searching Neural Network Operations

FetchingNAS is different from other NAS models since it’s not trying to create a graph. FetchingNAS is focusing on the operations and passing more right of control to the Agent. Therefore, the agent has the right to select the weights and the operation it wants.

![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/Steps.png?raw=true)
![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/ControllerAndSharedModel.png)

### Training on MNIST (for 70 epochs < Roughtly 6 hours on one GPU >):

![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/Train_Hist_Rewards.png?raw=true)


### The results show they use the same weight repetitively
#### Best Dag
<img src="https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/Best%20dags.png?raw=true" width="600" height="100">




#### Training on Cifar10:

![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/Cifar10_TrainingHist.png?raw=true)
![](https://github.com/ChihchengHsieh/FetchingNAS/blob/master/imgs/Cifar10_TrainingHist2.png?raw=true)
