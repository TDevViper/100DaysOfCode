# Day 3: Reinforcement Learning — Environment Setup and Basics

## 🔹 What is an Environment in RL?
In RL, the environment is the world in which the agent operates.
It provides:
- State (s) → what the agent “sees” right now
- Actions (a) → what the agent can do
- Rewards (r) → feedback after each action
The goal: learn a policy that maximizes rewards.

## 🏙️ Real Environment
Definition: Physical or live system interaction  
Examples: Robot arm, self-driving car, stock bot  
Challenges: Expensive, dangerous, slow, not reproducible

## 🧪 Simulated Environment
Definition: Virtual model of the world (Atari, Gym, MuJoCo)  
Benefits: Safe, cheap, fast, reproducible  
Limitations: “Reality Gap”

## 🎮 Episodes
One full run of an environment task.  
- Fixed episode length (e.g., CartPole = 200 frames)  
- Continuous tasks (e.g., Breakout = till failure)

