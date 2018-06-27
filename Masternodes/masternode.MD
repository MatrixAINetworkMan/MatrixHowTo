# MATRIX Masternodes

Yeah, everyone wants to have a MATRIX masternode.


## How many kinds of masternodes will be there?

There are mainly two kinds of masternodes in the MATRIX project: Mining masternodes and Verification masternodes.

A mining masternode requires a deposit of 10K MAN and processing power to run 1,000 TPS.

A verification masternode requires a deposit of 100K MAN deposit and processing power to run 2,000 TPS.

There are another two kinds of normal nodes, called AI service nodes and AGENT nodes. 

As for AI service nodes, there's no deposit requirement, as they simply provide processing power outputs.

As for Agent nodes, there's no deposit requirement either, and they serve as agents for a distributed computing processor.

Finally there are Dark Guardians, who:

Provide real-time monitoring throughout the network to root out bad actors. Specifically, they will use double-entry accounting methods to log and verify transactions for every account.

The MATRIX Foundation itself will deploy a dark guardian node and publish the related verified codes.
The Dark Guardian role is a voluntary contribution, but upon reporting fraudulent activity, they can be rewarded by the Foundation.


## What are the requirements for being a masternode?

A MATRIX masternode should reach a computing power of 1000TPS and make a deposit of 10,000 MANs. Besides, it needs to support RPC, and provide mining or other services

## Can you anticipate the ROI for Masternode?

ROI in the MATRIX project can be estimated based on the following model:

1.Of the remaining 40% of *1billion tokens:   

-25% will be distributed to miners  

-20% will be distributed to those who help with verification

-50% will be distributed to power contributors doing AI computing

The remaining 5% of tokens will be used to reward our MATRIX community and distributed according to community votes. 

This is the distribution ratio proposed by our MATRIX Dev team. We’re asking for consensus from the whole community to finalize the plan. 

We plan to share a distribution proposal every 6 months, then we will introduce a voting mechanism to survey the community. 

If no consensus is reached, we will go back to our initial proposal. 
And, we will switch to another one when possible.

2.Our MATRIX PoW verification is based on the random selection of 21 masternodes. 
Each masternode will be awarded 10% of the average mining rewards for a specified interval -- provided it is online long enough. 

The remaining 90% will be distributed based on a competition of computing power.  
When a miner is selected as a masternode, it will get a basic reward based on three rankings: 

1) Service time 

2) Deposits

3) and TPS. 

A miner can then compete for the remaining 90% of mining rewards based on computing power.  
The MCMC algorithms used for mining are created by CPU-like/GPU-like algorithm generator. 

3.In order to increase ROI and maximize rewards, 
we recommend people to deploy as much AI and CPU computing power as possible for external service. 

All computing power in the network will be pooled together. 
Any node sharing its computing power to work on an assignment will get a specific amount of reward, according to its share of the total work.

## Can you talk about Miner network, such as node selection?

![](https://i.imgur.com/zApUKo4.png)

This design aims at providing a steady and reasonable time interval for computing power leasing. Meanwhile, it ensures every masternode has the chance of competing for the role of supernode, to take the job of mining or validating. Based on our statistics, any one of the masternodes will have the opportunity of being a supernode every two weeks, even if there are 10,000 masternodes.

From the perspective of architecture, we will start the calculation of each miner's value first. And the calculated value system will be set as the basis of the probability of selection. The currently suggested evaluation criteria is as follows:

![](https://i.imgur.com/cPQVzIW.png)