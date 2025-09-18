# Robotic Arm Reach with PPO

I built a Deep Reinforcement Learning agent that controls a simulated Franka Panda robot arm, training it to reach target points in 3D space. This project was developed after completing the Hugging Face Deep RL Course.

The agent uses the PPO algorithm from Stable-Baselines3 and was trained in the `PandaReachDense-v3` environment for over one million timesteps across parallel simulations.
This project demonstrates the advantage of RL—the agent learned to solve the task through trial, error, and reward, without any pre-programmed movements. It successfully generalizes to reach for points it has never seen before.

This precise reach task is a foundational step for more complex manipulation tasks like pick-and-place, which I am working on next.
