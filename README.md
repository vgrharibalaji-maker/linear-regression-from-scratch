# Linear Regression from Scratch

A simple linear regression model built entirely from scratch using NumPy — no scikit-learn or other ML libraries used for the core algorithm.

## What it does
Predicts a student's exam score based on hours studied, using a manually implemented:
- Prediction function (`y = m*x + c`)
- Loss function (Mean Squared Error)
- Gradient Descent training loop to learn `m` and `c`

## How it works
1. Define input (hours studied) and output (exam scores) data
2. Make predictions using random initial `m` and `c`
3. Measure error using Mean Squared Error
4. Use gradient descent to iteratively update `m` and `c` to minimize error
5. Use the trained model to predict scores for new hours values
6. Visualize the data and learned line using Matplotlib

## Tools used
- Python
- NumPy
- Matplotlib

## Result
After training, the model learned the relationship between hours studied and exam score, with loss decreasing from ~3848 to ~1.17 over 1000 epochs.

## How to run
Open the notebook in Google Colab or Jupyter Notebook and run all cells in order.
