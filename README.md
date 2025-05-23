🏦 **Banking Domain Exploratory Data Analysis (EDA) Project**

📌 **Problem Statement**
Understand how data can be used in banking to minimize lending risk. This project aims to develop a basic understanding of customer behavior in the banking domain using Exploratory Data Analysis (EDA), which helps in risk analytics and better financial decision-making.

📊 **Project Overview**
This project demonstrates how EDA techniques can be used to uncover meaningful insights in the banking sector. The workflow includes collecting customer banking data, storing it in a MySQL database, and performing EDA using Python in Jupyter Notebook. Key insights are derived by analyzing various factors such as income, age, savings, deposits, loans, and more.

🗂️ **Data Source**
The CSV dataset used in this project is demonstrating a bank marketing dataset. The dataset is also provided in the GitHub repository. This dataset basically contains information about bank details, various client details which consists of multiple tables which are interlinked with each other through keys like primary key and foreign key.

The various tables are Banking Relationship, Client-Banking, Gender, Investment Advisor and Period.

It contains Key features such as:
Name, Age, Occupation, Nationality, Banking Contact, Estimated Income, Superannuation Savings, Amount Credit Cards, Credit Card Balance, Bank Loans, Bank Deposits, Checking Account, Saving Account, Gender

🛠️ **Technologies Used**
- Database: MySQL Workbench - For data storage and schema exploration
- Notebook Environment: Jupyter Notebook - For performing analysis and visualization
- Programming Language: Python
- Python Libraries:
    - pandas – Data manipulation and cleaning
    - numpy – Numerical operations
    - matplotlib, seaborn – Data visualization
    - mysql.connector – Database connectivity

🔄 **Project Workflow**
Data Collection: Imported CSV data and stored it in MySQL Workbench.
Database Connection: Connected MySQL with Jupyter Notebook using mysql.connector.
Data Extraction: Retrieved and loaded data into a pandas DataFrame using SQL queries.
Exploratory Data Analysis (EDA): 
    - Checked data types and missing values
    - Performed univariate and bivariate analysis
    - Visualized data distributions and correlations
Insights Generation: Derived actionable insights regarding customer financial behavior.

🔍 **Key Insights**
  - Consistent Depositors Are Likely to Save More
      - Customers who make regular deposits tend to also grow or maintain their savings accounts.
  - Older and Higher-Income Individuals Accumulate More Wealth
      - Age and income are positively correlated with superannuation, savings, and checking account balances.
  - Property Ownership Is Not a Strong Indicator of Financial Behavior
      - Property ownership shows low correlation with account activities, likely due to external non-banking factors.
  - Business and Personal Banking Behaviors May Overlap
      - Moderate correlation between business lending and personal loans suggests mixed-use cases, although business banking largely forms a distinct customer segment.

📈 **EDA Highlights**
    - Strong link between Bank Deposits and Savings Accounts
    - Age and Income correlate with higher account balances
    - Properties Owned show minimal impact on banking behavior
    - Business lending is moderately related to personal Bank Loans only

🚀 **Future Work**
  - Create a dashboard to visualize metrics like total loans, deposits, and savings across various customer segments
  - Use insights to identify which types of banks attract the most clients
  - Analyze nationality-based lending and account trends
  - Help stakeholders make data-driven decisions with real-time visuals




