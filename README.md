# IEEE-I06-UAV-DRL
Static environment
There are four methods to solve:

MADDPG
Fully Centralized DDPG
Fully Decentralized DDPG
Fully Centralized TD3
The third and the fourth methods perform better than others

Dynamic environment
There are four methods to solve:

PPO+GAE(with multi-processing )
TD3
DDPG
SAC
The first three methods perform just the same. PPO convergence needs less episodes. TD3 and DDPG converge fast. Though Soft Actor-Critic is an outstanding algorithm in DRL, it has no obvious effect in my environment.
