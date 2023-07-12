
# Customer Churn Prediction for a Telecommunications Company

## Analyzing IBM Telecommunications Data 
- The original [IBM dataset](https://www.ibm.com/docs/en/cognos-analytics/11.1.0?topic=samples-telco-customer-churn]).

### Problem Statement

The main objective of this project is to develop an advanced predictive model that accurately identifies customers at high risk of churn for a telecommunications company. By predicting customer churn, the company can implement targeted retention strategies and mitigate customer attrition, leading to improved customer satisfaction and increased profitability.

### Dataset

The dataset used in this project is sourced from Kaggle and contains information about customer characteristics in the telecommunications industry. The dataset consists of nineteen columns, including demographic details, account information, and service details. The response variable, "Churn," indicates whether a customer has terminated their relationship with the company. The dataset allows us to explore the relationship between customer characteristics and churn behavior.

### Project Steps

To address the problem, we will follow a systematic approach with the following steps:

1. Data Reading: Load the dataset into the analysis environment.
2. Exploratory Data Analysis and Data Cleaning: Gain insights into the dataset, address data quality issues, and preprocess the data.
3. Data Visualization: Visualize the data to understand the distribution and relationships between variables.
4. Feature Importance Analysis: Identify the significant features that predict customer churn.
5. Feature Engineering: Enhance the dataset by creating new features or extracting meaningful information.
6. Establishing a Baseline: Develop an initial model as a benchmark for future comparisons.
7. Splitting the Data into Training and Testing Sets: Divide the dataset for model training, validation, and evaluation.
8. Evaluating Multiple Algorithms: Apply various machine learning algorithms and assess their performance.
9. Algorithm Selection: Choose the most effective algorithm for customer churn prediction.
10. Hyperparameter Tuning: Optimize the selected algorithm by fine-tuning its hyperparameters.
11. Model Performance Assessment: Evaluate the final model's performance using comprehensive evaluation metrics.
12. Drawing Conclusions and Providing a Summary: Summarize the findings, derive actionable insights, and recommend churn reduction strategies based on the predictive model.
13. Limitations and Future Work: Discuss the project's limitations and propose areas for further research and improvement.

By following the steps outlined in the project and utilizing the provided resources, you can apply customer churn prediction techniques to the telecommunications industry and make data-driven decisions to enhance customer retention and business profitability.

### Repository Structure

The repository is organized as follows:

- `data/`: Contains the dataset used for the project (e.g., `Telco_Customer_Churn.csv`).
- `notebooks/`: Jupyter notebooks with the code for data preprocessing, model training, evaluation, and hyperparameter tuning.
- `models/`: Saved models or model artifacts generated during the project.
- `results/`: Generated results and evaluation metrics (e.g., CSV files, plots, etc.).
- `README.md`: This README file providing an overview of the project and repository.
- `requirements.txt`: Lists the required Python libraries and dependencies for running the code.

### Getting Started - Usage

To get started with this project, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/M-cell27/customer-churn-prediction.git
   ```

2. Install the required Python libraries and dependencies using `pip`:
   ```
   pip install -r requirements.txt
   ```

3. Explore the Jupyter notebooks in the `notebooks/` directory to understand the project workflow and code implementation.

4. Run the notebooks in sequential order to preprocess the data, train and evaluate the models, and perform hyperparameter tuning.

5. Refer to the `results/` directory for generated evaluation metrics, plots, and any other project outputs.

### License

This project is licensed under the [MIT License](LICENSE).

### Contribution

Contributions to this project are welcome. If you have suggestions, bug reports, or improvements, please feel free to open an issue or submit a pull request.

### Contact

For any inquiries or questions, please contact [Melo Sepulveda](mailto:ms.santiago.wrk@gmail.com).
