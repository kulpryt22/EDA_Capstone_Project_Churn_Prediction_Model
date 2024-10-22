### Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a customer churn dataset. Churn refers to customers who have stopped using a service, and this analysis helps in identifying patterns and key factors influencing customer churn. By understanding these factors, we can take actionable steps to reduce churn rates, improve customer retention, and ultimately drive business growth. 

### Dataset

The dataset used for this project contains customer data, including demographics, account information, service subscriptions, and churn status. The key columns include:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Customer's gender.
- **Tenure**: How long a customer has been with the company.
- **Contract**: Type of contract the customer has.
- **Payment Method**: Payment method chosen by the customer.
- **Churn**: Binary variable indicating whether the customer churned.

The dataset consists of X records and Y features.

### Project Objectives

- **Understand the customer demographics** and subscription details.
- **Identify factors contributing to customer churn** using data visualizations.
- **Prepare the data** for further machine learning applications if necessary.
- **Identify multicollinearity** to clean the dataset and ensure better performance for predictive modeling.

### Steps Followed

1. **Data Loading and Inspection**:
    - Load the dataset and inspect the first few rows.
    - Check for missing values and understand the structure of the data.

2. **Data Cleaning**:
    - Handle missing values.
    - Convert appropriate columns (like `tenure`, `monthly charges`) into numerical types.
    - Encode categorical variables such as `Gender`, `Contract`, and `Payment Method`.

3. **Data Exploration**:
    - Perform univariate and bivariate analysis.
    - Analyze the distribution of customer churn across various features like gender, tenure, contract type, etc.
    - Use statistical summaries to understand relationships between churn and other variables.

4. **Feature Engineering**:
    - Create new features based on existing ones (if needed).
    - Normalize or scale continuous features like `MonthlyCharges`.

5. **Data Visualization**:
    - Visualize correlations between features using heatmaps.
    - Create boxplots, histograms, and bar charts to show distributions and relationships.
    - Analyze multicollinearity using **Variance Inflation Factor (VIF)**.

6. **Model Readiness**:
    - Prepare the dataset for machine learning by selecting and encoding features, handling outliers, and identifying potential predictive variables.

### Key Visualizations
- **Distribution of Customer Churn**: Visualize how many customers churned vs stayed.
- **Gender vs Churn Rate**: Analyze if there’s any difference in churn rate between male and female customers.
- **Contract Type and Churn**: Determine whether customers with longer contracts tend to churn less.
- **Monthly Charges vs Churn**: Understand how higher or lower charges influence customer churn.
- **Tenure and Churn**: Study the correlation between customer tenure and their likelihood of churning.

### Technologies Used
- **Python**: For data analysis and visualization.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib & Seaborn**: For creating data visualizations.
- **Statsmodels**: For multicollinearity analysis using VIF.
- **Jupyter Notebook / Google Colab**: For project development and code execution.

### How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-repo/churn-prediction-eda.git
   ```
2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Google Colab for the EDA process.

### Conclusion

This EDA provides a solid understanding of the key factors influencing customer churn. The insights gained can be further used to build predictive models to classify and predict customer churn and aid in business decisions aimed at reducing churn rates.

### License

This project is licensed under me - see the LICENSE.md file for details.
