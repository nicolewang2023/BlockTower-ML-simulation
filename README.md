# BlockTower-ML-simulation

This project simulates block tower stability using a physics engine (or a surrogate function) and applies machine learning to predict whether a given tower configuration will remain upright. It combines physical simulation, structured data collection, and model training to model intuitive physics.

## Objective

To predict the stability of randomly generated block towers using x-positions as input features. The project demonstrates the integration of simulation-based data and supervised learning for classification.

## Features

- Simulates 200 block tower trials, each with randomized block positions
- Uses a surrogate physics engine to estimate tower outcome
- Saves trial data to a CSV file for reproducibility
- Trains a logistic regression classifier on tower position data
- Evaluates prediction accuracy and reports performance metrics

## Technologies

- Python
- `numpy`, `csv`
- `scikit-learn` (classification, model evaluation)
- Optional: `pygame`, `pymunk` (for full physics integration)

## How to Run

Install dependencies:

```bash
pip install numpy scikit-learn matplotlib
