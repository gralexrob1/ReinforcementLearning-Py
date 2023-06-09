> https://gymnasium.farama.org/

**gymnasium**  
```!pip install gymnasium```  
```import gymnasium as gym```

*Methods*  
```gym.make()``` chooses universe  
```env.reset()``` starts the game  
```env.step(action)``` takes a step and returns ```(observation, reward, done, terminated, info)```  
```env.seed()``` initializes random state

*Attributes*  
```gym.Env.action_space``` available actions  
```gym.Env.reward_range``` rewards
