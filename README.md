# S-Mobile-Predicting-Customer-Churn

## Project Description
In this initiative, I was tasked with developing a predictive model for S-Mobile, a top cellphone carrier in Singapore, to predict customer churn. The goal was to identify customers at risk of leaving before they took any action, enabling proactive retention strategies. This involved analyzing extensive customer data, building various machine learning models, and delivering actionable insights to mitigate churn.

## Technology Stack
- **Data Handling and Scripting**: Python, pandas, pyrsm
- **Machine Learning Models**: Logistic Regression, XGBoost, Random Forest, Neural Networks
- **Visualization and Evaluation**: Matplotlib, Partial Dependence Plots (PDP), Permutation Importance

## Key Accomplishments

### Data Integration and Preparation
- **Data Loading**: Processed a dataset with 1 million rows and 25 variables detailing customer demographics and behavioral patterns.
- **Data Exploration**: Performed exploratory data analysis to identify key features influencing customer retention such as revenue, usage, and service interactions.

### Model Development and Analysis
- **Baseline Model**: Developed a logistic regression model to establish a baseline for churn prediction.
- **XGBoost Model**: Built an XGBoost model that outperformed others with an AUC score of 0.761, making it the chosen model due to its accuracy and robustness.
- **Alternative Models**: Tested Random Forest and Neural Networks, achieving AUC scores of 0.737 and 0.719 respectively, demonstrating potential but not surpassing XGBoost.

### Key Drivers of Churn
- **Variable Importance**: Utilized Permutation Importance and PDPs to identify significant churn predictors including:
  - **Equipment Usage Time (eqpdays)**: Older handsets correlated with higher churn.
  - **Months of Service (months)**: Newer customers showed greater churn risk.
  - **Overage Usage (overage)**: Excessive overage was a dissatisfaction indicator.
  - **Revenue**: Lower revenue levels were associated with higher churn.
  - **Customer Service Interactions (retcalls)**: Multiple retention calls signaled impending churn.

### Actionable Insights and Interventions
- **Upgrade Incentives**: Suggested handset upgrades for customers with outdated devices to reduce churn.
- **Customized Plans**: Recommended tailored plans for customers frequently exceeding their usage limits.
- **Enhanced Customer Service**: Advocated for improved service quality, particularly for customers with multiple retention calls.
- **Occupation-Based Services**: Proposed services tailored to customer occupation profiles for increased relevance and engagement.

### Economic Impact Analysis
- **Customer Lifetime Value (CLV)**: Conducted CLV analysis to measure the economic impact of retention strategies over a 5-year horizon.
- **Retention Enhancements**: Analyzed how improving service for high-contact customers could significantly boost CLV.
- **Handset Upgrades**: Evaluated the CLV uplift from offering handset upgrades to customers with older models.
- **Overage Management**: Assessed the CLV increase from better-aligned service plans for high overage users.

## Key Outcomes
- **Improved Predictive Accuracy**: The XGBoost model provided precise and dependable churn predictions, enhancing the effectiveness of retention strategies.
- **Actionable Business Insights**: Detailed analysis revealed key churn drivers, enabling the creation of focused interventions to decrease churn and bolster customer loyalty.
- **Economic Viability**: CLV calculations validated the financial advantages of the proposed strategies, advocating their adoption for S-Mobile's churn management efforts.
