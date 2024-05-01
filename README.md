# Taxi Profit Maximization with Reinforcement Learning

This repository contains code for a project focused on maximizing taxi driver profits using reinforcement learning (RL) algorithms. The goal is to develop an RL agent that learns to select profitable taxi trips based on historical data.

## Overview

Taxi drivers have to decide which trips to accept to maximize their daily earnings. This project implements RL algorithms that learn optimal decision-making policies for selecting taxi trips. The RL agent interacts with a simulated environment based on historical taxi trip data to learn and improve its decision-making process over time. Our dataset is gotten from [NYC taxi drivers dataset](https://www.andresmh.com/nyctaxitrips/).  

## Implementation

The project includes:

- Data preprocessing: Cleaning and transforming raw taxi trip data for RL training in `taxi_trips.ipynb`.  
- Environment setup: Creating a simulated taxi hailing service environment for RL agent interaction in `RLProject.ipynb`.  
- RL algorithms: Implementing various RL algorithms, including Q-learning, SARSA, deep Q-learning, and double deep Q-learning in `RLProject.ipynb`.  
- Evaluation: Assessing the performance of RL agents in maximizing taxi driver profits using metrics such as reward mean and reward standard deviation in `RL Report.pdf`.  

## Usage

To use the code in this repository:

1. Clone the repository to your local machine.  
3. Run the main scripts for data preprocessing, environment setup, and RL algorithm training.  
4. Evaluate the trained RL agents and analyze their performance for yourself.  

## Future Work

Future improvements and extensions to this project may include:

- Refining the RL algorithms for better performance and convergence.  
- Enhancing the simulation environment to better reflect real-world taxi operations.  

## Contributors

- [Abdulmueez Emiola](mailto:a.emiola@innopolis.university)
- [Ozioma Okonicha](mailto:o.okonicha@innopolis.university)
- [Pavel Tishkin](mailto:p.tishkin@innopolis.university)

