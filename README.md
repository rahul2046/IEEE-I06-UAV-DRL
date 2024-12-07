# IEEE-I06-UAV-DRL
Static environment


#There are four methods to solve:

 1.ADDPG
 2.Fully Centralized DDPG
 3.Fully Decentralized DDPG
 4.Fully Centralized TD3
The third and the fourth methods perform better than others


Dynamic environment
There are four methods to solve:

1.PPO+GAE(with multi-processing )
2.TD3
3.DDPG
4.SAC
The first three methods perform just the same. PPO convergence needs less episodes. TD3 and DDPG converge fast. Though Soft Actor-Critic is an outstanding algorithm in DRL, it has no obvious effect in my environment.
