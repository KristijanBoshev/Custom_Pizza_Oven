# PizzAI Oven: Reinforcement Learning Custom Environment



## Overview


The PizzAI Oven is a custom environment designed for reinforcement learning tasks. In this environment, agents aim to cook the perfect pizza by learning to control the oven's parameters effectively. The environment simulates the process of baking a pizza in an oven, allowing agents to learn optimal policies for achieving the desired outcome.

## Usage
```python
1. git clone https://github.com/KristijanBoshev/Custom_Pizza_Oven.git
2. Open the .ipynb file
3. Add '#' before model.learn(...)
4. Then, load the pre-trained model using the following command:
 model = PPO.load("<path of the .zip locally>", env)
```

## Environment details

The PizzAI Oven environment is initialized with the following parameters:

- **Action Space**: The set of possible actions that the agent can take in the environment.
- **Observation Space**: The range of temperatures within which the oven operates.
- **Cooking Time**: The duration for which the pizza is cooked.
- **Reward System**: The mechanism used to calculate rewards based on the agent's actions and the ideal temperature.
- **Current State**: The starting temperature of the oven.

## Bon appétit!  
        
