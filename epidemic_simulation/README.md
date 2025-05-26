# 🧪 Agent-Based Epidemic Simulation (SIR Model)

This project simulates the spread of an epidemic using an **agent-based model** built with **object-oriented programming**. The simulation incorporates **spatial and temporal dynamics** to represent realistic geographic interactions between individuals and the transmission dynamics of an infectious disease based on the **SIR (Susceptible–Infected–Recovered)** model.

## 🎯 Project Objective

To build a tool that helps explore and visualize how an epidemic spreads through a population, and how different parameters or control strategies (e.g., infection rate, recovery rate, isolation measures) affect the outcome of the epidemic.

## 🧰 Features

- **Agent-based modeling**: Each individual is represented as an autonomous agent with their own health state and position.
- **SIR framework**: Tracks the status of individuals as Susceptible, Infected, or Recovered.
- **Spatial dynamics**: Interactions are limited by geographic proximity between agents.
- **Temporal evolution**: The simulation updates over time steps, modeling infection and recovery processes.
- **Parameter control**: Easy tuning of infection and recovery rates.

## 💡 Key Insights

- The model reproduces patterns consistent with classic epidemiological behavior (such as peak infections and herd immunity).
- The simulation can help test different public health strategies by adjusting parameters or movement restrictions.
- Spatial constraints play a critical role in disease spread and containment.

## 🛠 Technologies Used

- Python (Object-Oriented Programming)
- Matplotlib (for visualizing simulation results)
- NumPy (for numerical operations)
- Jupyter Notebook (optional interface for interactive exploration)

## 🧪 How to Run the Simulation

```bash
git clone https://github.com/yourusername/epidemic-simulation.git
cd epidemic-simulation
python simulation.py
