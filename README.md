# Can an AI Survive a Horror Movie?

What happens when you put an AI inside a horror scenario and let the monsters hunt it?

This project uses **Unity and ML-Agents** to train an autonomous agent through reinforcement learning. The agent must navigate the environment, reach its objectives, avoid obstacles, and learn how to survive against different monsters.

Each monster is designed to create a different challenge, forcing the agent to adapt its behavior instead of learning a single escape strategy.

## The Experiment

The agent begins with no knowledge of the environment or how to survive.

Through repeated training, rewards, penalties, and environmental perception, it gradually learns behaviors that help it reach its objective while avoiding danger.

The project explores how changes in enemies, environments, perception, and reward functions affect the strategies learned by the agent.

## The Monsters

### The Scarlet Monster

The first enemy introduced in the project.

The Scarlet Monster actively pursues the agent through the environment, creating a constant threat while the agent attempts to reach its objective.

More monsters and survival scenarios are planned, each with different behaviors and challenges.

## How the AI Learns

The agent is trained with **Unity ML-Agents** using:

- Reinforcement learning
- Reward shaping
- Ray perception sensors
- Navigation and obstacle avoidance
- Enemy pursuit behaviors
- Iterative training and parameter tuning

## Tech Stack

- Unity
- Unity ML-Agents
- Python
- Reinforcement Learning
- Ray Perception Sensors
- NavMesh

## Why Horror?

Most reinforcement learning environments are built around abstract objectives: reach a target, collect a reward, or avoid an obstacle.

I wanted to turn the same ideas into something more memorable.

Instead of simply asking whether an AI can navigate a map, this project asks:

**Can an AI learn how to survive a horror movie?**

And as new monsters appear, the answer may have to change.
