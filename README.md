# Reinforcement-Learning  

**场景**:[FrozenLake-v1](https://www.gymlibrary.dev/environments/toy_text/frozen_lake/)        **方法**:`DQN`  
**核心**:`TD(0)`    
`colab代码`:[DQN](https://github.com/zoujiulong/Reinforcement-Learning/blob/main/DQN.ipynb)  
**注**：经验回放不要任意使用，以该场景为例，只有终点奖励值为1，如果经验回放很可能sample都是无用的轨迹，网络学不到任何东西.  

**场景**:[CartPole-v1](https://www.gymlibrary.dev/environments/classic_control/cart_pole/)        **方法**:`DDQN`  
`colab代码`:[DDQN](https://github.com/zoujiulong/Reinforcement-Learning/blob/main/DDQN.ipynb)  
 

**场景**:[CartPole-v1](https://www.gymlibrary.dev/environments/classic_control/cart_pole/)        **方法**:`PPO`结合`MC`  
`Actor loss`、策略比例、`Critic loss`(同下)  
`colab代码`:[PPO(MC)](https://github.com/zoujiulong/Reinforcement-Learning/blob/main/PPO(MC).ipynb)    
**注**：由于奖励都是1，`TD`方法不适合该场景.  

**场景**:[LunarLander-v3](https://www.gymlibrary.dev/environments/box2d/lunar_lander/)         **方法**:`PPO`结合`GAE`  
`Actor loss`:![image](https://github.com/user-attachments/assets/54754593-d94f-45d3-978e-690870838fd2)  
其中策略比例为：  
![image](https://github.com/user-attachments/assets/bf6c3e78-8fa8-47fc-8159-eaec714e0308)  
`Critic loss`：  
![image](https://github.com/user-attachments/assets/c1d50314-0062-4eda-904b-ca0ede6bdfbe)    
`colab代码`:[PPO(GAE)](https://github.com/zoujiulong/Reinforcement-Learning/blob/main/PPO.ipynb)

