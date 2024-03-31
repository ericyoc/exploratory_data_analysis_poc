# Customer Segmentation Analysis

This repository contains a Python script that demonstrates customer segmentation analysis using the "Mall Customers" dataset. The script combines, cleans, and pre-processes the data, performs exploratory data analysis (EDA), formulates and tests hypotheses, builds a linear regression model, and uses a machine learning model to make predictions.

## Dataset

The "Mall Customers" dataset used in this analysis can be found at the following link:
[Mall Customers Dataset](https://github.com/ericyoc/exploratory_data_analysis_demo/tree/main/ml_data)

The dataset contains information about customers of a mall, including their age, gender, annual income, and spending score.

## Prerequisites

To run the Python script, you need to have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/your-username/customer-segmentation-analysis.git
   ```

2. Download the "Mall Customers" dataset from the provided link and place it in the same directory as the Python script.

3. Open the Python script `customer_segmentation.py` in your preferred Python IDE or text editor.

4. Update the `file_path` variable in the `main()` function with the path to the "Mall Customers" dataset file.

5. Run the Python script:
   ```
   python customer_segmentation.py
   ```

6. The script will perform the following steps:
   - Combine, clean, and pre-process the data
   - Perform exploratory data analysis (EDA) and display visualizations
   - Formulate and test hypotheses
   - Build a linear regression model
   - Use a machine learning model to make predictions

7. The script will output the results, including visualizations, hypothesis test conclusions, model performance metrics, and predictions.

## Code Overview

The Python script `customer_segmentation.py` contains the following functions:

- `preprocess_data(file_path)`: Combines, cleans, and pre-processes the data from the given file path.
- `perform_eda(df)`: Performs exploratory data analysis on the DataFrame and displays visualizations.
- `test_hypotheses(df)`: Formulates and tests hypotheses based on the data.
- `build_linear_regression(df)`: Builds a linear regression model using the data.
- `predict_spending_score(df)`: Uses a machine learning model to predict the spending score for a new customer.
- `main()`: The main function that orchestrates the entire analysis process.

## Visualizations

The script generates the following visualizations:

1. **Figure 1 - Age Distribution**: This plot shows the distribution of customer ages in the dataset. It helps identify the most common age ranges and any potential outliers or unusual patterns in the age distribution. Understanding the age distribution is important for targeted marketing strategies and customer segmentation.

2. **Figure 2 - Age vs Spending Score**: This plot visualizes the relationship between customer age and their spending score. It helps identify any potential patterns or trends in spending behavior across different age groups. If a clear relationship is observed, it suggests that age may be a significant factor influencing spending habits, which can be valuable for targeted marketing and customer segmentation.

## Conclusion

The customer segmentation analysis performed in this script provides insights into the "Mall Customers" dataset. By exploring the data, testing hypotheses, building a linear regression model, and using a machine learning model for predictions, we can gain a better understanding of customer behavior and make data-driven decisions for targeted marketing and customer segmentation.

Feel free to explore the code, modify it, and adapt it to your specific needs. If you have any questions or suggestions, please feel free to open an issue or submit a pull request.
