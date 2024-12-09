# Home Credit Loan Prediction Project

Business Problem
Many individuals with limited or no credit history face difficulties obtaining loans, often resorting to unreliable lenders. Home Credit Group seeks to address this issue by expanding financial inclusion through safe and accessible loans. This project aims to enhance Home Credit's ability to predict loan repayment capabilities, enabling them to reach more clients without escalating default rates.

Proposed Solution
The solution involves developing a supervised machine learning classification model to predict whether a client can repay a loan. Leveraging historical data such as credit scores, monthly balances, and other relevant fields, the model will provide repayment probabilities for each client. These predictions will help Home Credit make informed decisions about loan approvals and terms, reducing defaults while extending opportunities to underserved individuals.

Benefits
Enhanced prediction accuracy will enable Home Credit to:

Approve loans for clients with repayment potential.
Reduce default rates and potential losses (estimated at $178.5M annually, $8.91B extrapolated over five years).
Offer tailored loan terms that set clients up for success.
Build trust with lenders by mitigating risks.
Analytics Approach
The project includes:

Exploratory Data Analysis (EDA): Evaluating data quality, identifying key features, and addressing issues such as class imbalance and missing values.
Data Preparation: Cleaning data by removing redundant features, handling missing values, and encoding categorical variables using methods like one-hot, label, and target encoding.
Modeling: Employing baseline and advanced models (Logistic Regression, Random Forest, XGBoost, and XGBoost+) with a focus on optimizing recall to accurately identify clients who are unlikely to default.
Key Insights & Presentation Highlights

Maximizing Identification of High-Risk Clients: The models achieved a recall rate of 0.75, improving the ability to flag high-risk borrowers.
Recall Focus: High recall ensures fewer clients at risk of default are misclassified as low-risk, reducing financial losses and building lender trust.
Risk-Based Strategies:
High-Risk Borrowers: Implement stricter approval criteria (higher collateral requirements, lower loan amounts, higher interest rates).
Medium-Risk Borrowers: Provide tailored options such as shorter loan terms or additional financial checks.
Low-Risk Borrowers: Extend competitive loan offers with confidence.
Customer Education: Introducing financial literacy programs ensures borrowers better understand their obligations and improves overall repayment rates.
Average Loan Impact: With an average loan amount of $557,778, the model’s improved risk stratification directly reduces exposure to significant losses.
Challenges & Solutions

Class Imbalance: Only 8% of clients in the dataset experienced payment difficulties. Advanced techniques like SMOTE, class weighting, and XGBoost helped address this issue.
Outliers: Extreme values, such as anomalies in "Days Employed," required careful handling to prevent skewed predictions.
Missing Values: Thoughtful imputation and feature reduction were employed to manage fields with over 50% missing data.
Deliverables
The project team (Group X) delivered the following by December 3, 2024:

EDA Notebook
Modeling Notebook
Final Presentation
GitHub Analytics Portfolio
Conclusion and Future Directions
While class imbalance posed significant challenges, the project successfully improved Home Credit’s ability to identify high-risk clients, ensuring loans are extended responsibly. Future steps include:

Expanding features with interactive terms and polynomial transformations.
Conducting more robust hyperparameter tuning.
Implementing financial literacy programs to improve borrower success rates.
This project underscores the importance of combining analytics, strategic lending practices, and customer education to drive financial inclusion and sustainable growth.
