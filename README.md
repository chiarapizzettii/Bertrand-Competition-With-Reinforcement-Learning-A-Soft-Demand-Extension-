# Bertrand Competition with Reinforcement Learning: A Soft Demand Extension

## **Project Overview**
This project explores the **classical Bertrand competition model** between two firms using **Reinforcement Learning**.
Unlike the standard Bertrand model, where a small price increase leads to losing the entire market, this project uses a **soft (Logit) demand function**. With this approach, a firm that raises its price loses market share gradually instead of instantly.

## **How It Works**
- The environment is implemented using the **PettingZoo** library to model a two-agent game.
- Each agent represents a firm that chooses its price at every step.
- Agents are trained using the **DDPG (Deep Deterministic Policy Gradient)** algorithm.
- Training is done through **self-play**, meaning agents repeatedly interact with each other in a one-shot game with **stochastic marginal costs**.

## **Results**
The simulation results are consistent with standard economic theory, confirming that the **Bertrand-Nash equilibrium** holds even in a Reinforcement Learning setting with soft demand.

## **Libraries**
- `PettingZoo`
- `Gymnasium`
- `NumPy`
- `Matplotlib`

### *Author: Chiara Pizzetti*
