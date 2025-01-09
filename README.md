# Continuum Robot Simulation and Training

## :pencil2: Description

This project implements the Deep Deterministic Policy Gradient (DDPG) algorithm for training an agent in a three-dimensional environment. The main goal is to create a model that can optimally interact with a complex environment, making decisions based on continuous actions.

## :file_folder: Project structure

- `model.py` : Implementation of the mathematical model of the robot.
- `DDPG.py` : Model training
- `environment.py` :Gym environment for robot simulation.
- `test.py` : Testing a trained agent.
- `visualization.py` : Visualization of the robot in 3D space.

## :checkered_flag: Features

- Simulation of the motion of a continuum robot in 3D space.
- Visualization of robot.
- Support for custom reward functions.

## :zap: Getting Started

### :mortar_board: Model training

Run `DDPG.py` to start learning:

```bash
python DDPG.py
```

### :computer: Testing the model

Run `test.py` to test the trained model:

``` bash
python test.py
```

### :globe_with_meridians: Visualization

Run `visualization.py` to see the robot's work in 3D space:

```bash
python visualization.py
```

## The process of training and testing the robot

<div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
  <img src="img/Training1.jpg" alt="Robot Action 1" style="width: 50%; max-width: 300px; border: 2px solid #ccc; border-radius: 8px;">
  <img src="img/Training2.jpg" alt="Robot Action 2" style="width: 50%; max-width: 300px; border: 2px solid #ccc; border-radius: 8px;">
</div>

## :bookmark_tabs: Сonclusion

The results of the project demonstrate the effectiveness of the DDPG algorithm for training an agent in complex environments with continuous actions. The use of neural networks for policy and criticism allowed us to achieve a high level of adaptation of the agent to new environmental conditions.
Further improvements may include optimizing hyperparameters, extending the model architecture, or implementing additional mechanisms such as prioritized repetition experience or more complex reward functions.

