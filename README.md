# Surgical Robot Simulator

A high-performance GPU-based simulation platform for reinforcement learning research with surgical robots. This project provides a realistic and efficient environment for developing and testing autonomous control algorithms, enabling rapid iteration and experimentation in surgical AI.

## Key Features
*   GPU-accelerated physics simulation for real-time performance.
*   Reinforcement learning-ready interface with standard gym APIs.
*   Modular surgical robot and task definitions for easy customization.
*   Support for procedural environment generation and domain randomization.

## Tech Stack
*   NVIDIA Isaac Sim / Omniverse
*   PyTorch
*   OpenAI Gym
*   Python

## Getting Started
```bash
git clone https://github.com/zoreanuj/surgical-robot-simulator.git
cd surgical-robot-simulator
pip install -e .
# Run a basic example
python examples/run_env.py
```