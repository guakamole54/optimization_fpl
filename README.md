# Optimization Methods in Game Strategies

This repository contains the practical part of my thesis focused on applying optimization techniques to strategic decision-making in games. The goal is to explore how different optimization approaches—such as linear programming, genetic algorithms, and machine learning—can be used to solve optimization problem of a Fantasy Premier League (FPL) optimal squad selection.

Each method is implemented and demonstrated using Jupyter notebooks.

# How to Start

1. Clone this repository:
```
git clone https://github.com/yourusername/optimization-game-strategies.git
cd optimization-game-strategies
```
2. Create a virtual environment (optional but recommended):
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. Install required dependencies:
```
pip install -r requirements.txt
```
4. Open Jupyter Lab or Notebook and run the cells in order:
```
jupyter lab
```

# Example Notebooks

## Linear Programming
Uses the PuLP library to model and solve the FPL optimization problem with linear constraints.

📁 File: linear_programming.ipynb

## Genetic Algorithms
Explores evolutionary algorithms to find near-optimal solutions in large and complex search spaces.

📁 File: genetic_algorithms.ipynb

## Machine Learning
Applies supervised learning models (Ridge Linear Regression, XGBoost, Random Forest, Neural Networks) to the FPL optimization problem.

📁 File: machine_learning.ipynb


## Tech Stack
Python 3.x

Jupyter Notebooks

Libraries: pulp, numpy, pandas, scikit-learn, matplotlib, seaborn, deap (see requirements.txt)

## Contact
For questions or collaboration ideas, feel free to reach out via GitHub Issues or email.