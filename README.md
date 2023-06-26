> https://gymnasium.farama.org/
> https://gymnasium.farama.org/api/env/

**gymnasium**  
```!pip install gymnasium```  
```import gymnasium as gym```

*Methods*  
```gym.make()``` chooses universe  
```env.reset()``` starts the game  
```env.step(action)``` takes a step and returns ```(observation, reward, done, terminated, info)```  
```env.seed()``` initializes random state

*Attributes*  
```gym.Env.observation_space``` observation space    
```gym.Env.action_space``` available actions  
```gym.Env.reward_range``` rewards  
```gym.Env.metadata``` metadata  
```gym.Env.spec``` information used to initialize env

