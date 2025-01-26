# Loss Functions and Accuracy in Regression

This repository demonstrates a simple implementation of linear regression from scratch, focusing on calculating common metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score to evaluate model performance.

## Features

- **Linear Regression**: Implements the model training (`fit`) and prediction (`predict`) methods.
- **Evaluation Metrics**:
  - **MAE**: Measures the average magnitude of errors in predictions.
  - **MSE**: Quantifies the average squared difference between actual and predicted values.
  - **R² Score**: Indicates how well the model explains the variance in the target variable.

## Code Example

The implementation includes the following steps:
1. Data preparation.
2. Model training using the `fit` method.
3. Making predictions with the `predict` method.
4. Calculating metrics (MAE, MSE, and R² Score).

Example outputs:
```plaintext
MAE: 0.8
MSE: 1.05
R² Score: 0.89
```

## Usage

1. Clone the repository:
   ```bash
   https://github.com/AlirezaMz10/accuracy-and-loss-regression.git
   ```
2. Run the script:
   ```bash
   python main.py
   ```

## Requirements

- Python 3.6+
- NumPy

Install dependencies:
```bash
pip install numpy
```

## License

This project is licensed under the MIT License.

