# OIBSIP-TASK-5
SALES PREDICTION USING PYTHON
# Sales Prediction Model

This repository contains a machine learning model for predicting sales based on advertising spending. The model uses linear regression to establish relationships between advertising spending on different platforms and corresponding sales values.

## Dataset

The dataset used for training and testing the model contains the following features:

- **TV**: Advertising spending on TV
- **Radio**: Advertising spending on radio
- **Newspaper**: Advertising spending on newspaper
- **Sales**: Sales value (target variable)

The data is provided in a CSV file named `Advertising.csv`.

## Model Selection

For this sales prediction task, the Linear Regression model was chosen due to its effectiveness in predicting continuous values. The model was selected over other algorithms like K-Nearest Neighbors for its ability to handle continuous target variables and produce interpretable results.

## Evaluation

The model was trained on a subset of the data and evaluated on a separate test set. The evaluation metrics used were:

- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual sales values.
- **R-squared (R2)**: Represents the proportion of variance in the target variable explained by the model.

The achieved low MSE and high R-squared values indicate the model's good performance in accurately predicting sales values.

## Instructions

To use the sales prediction model, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Python and the required libraries (pandas, scikit-learn) installed.
3. Run the `SALES_PREDICTION_USING_PYTHON.ipynb` script to train the model and evaluate its performance.
4. The script will display the Mean Squared Error and R-squared values as evaluation metrics.
5. You can also modify the script to load your own sales data for prediction.

## Requirements

- Jupyter Notebook(Python 3)
- pandas
- scikit-learn

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to modify, enhance, and use this model for your own sales prediction tasks.

If you find this project useful or have any suggestions for improvement, please feel free to contribute or create issues.

Happy predicting! 🚀

---
