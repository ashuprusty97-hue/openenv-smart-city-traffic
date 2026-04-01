# openenv-smart-city-traffic
An OpenEnv-style reinforcement learning environment simulating real-world traffic signal optimization with scalable and extensible design.
# Smart Traffic Control RL Environment

## Overview
This project presents a real-world inspired reinforcement learning environment designed to optimize traffic signal control at an urban intersection. The environment follows a standard OpenEnv-style API using step(), reset(), and state() methods.

## Objective
To enable an AI agent to learn optimal traffic signal switching strategies that:
- Reduce vehicle waiting time
- Minimize congestion
- Improve overall traffic flow

## Environment Design

### State Space
The agent observes:
- Queue length from North, South, East, West directions
- Current traffic signal state
- Time elapsed

### Action Space
- 0 → Keep current signal  
- 1 → Switch signal  

### Reward Function
- Penalizes high congestion and delays  
- Rewards reduction in total queue length  

## Project Structure

## How to Run

pip install -r requirements.txt  
python examples/run_random_agent.py  

## Key Features
- OpenEnv-style API (step, reset, state)
- Real-world inspired traffic simulation
- Lightweight and easily extensible design
- Suitable for reinforcement learning algorithms such as DQN and PPO

## Future Improvements
- Multi-intersection traffic network
- Multi-agent reinforcement learning
- Integration with deep RL frameworks
- Visualization dashboard

## Author
Ashutosh
