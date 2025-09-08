![preview](https://github.com/d28006/HR-Analytics/blob/main/Snapshot%20of%20Dashboard.PNG)

1. Project Title / Headline

👥 Employee Churn Prediction Dashboard: Proactive Insights for Retention
An interactive Looker Studio dashboard powered by AutoML churn modeling to identify at-risk employees, uncover key drivers of attrition, and provide HR leaders with data-driven recommendations for improving retention and employee satisfaction.

2. Short Description / Purpose

The Employee Churn Prediction Dashboard enables HR teams to monitor attrition risk across departments, evaluate the most influential factors driving turnover, and anticipate employee exits before they occur. By combining machine learning predictions with intuitive visuals, this dashboard empowers organizations to proactively address churn and design effective retention strategies.

3. Tech Stack

This end-to-end churn model project was built using:

• 🗄 Google BigQuery – Cloud data warehouse to store, query, and manage historical HR data

• 🐍 Python (Google Colab) – For connecting to BigQuery, cleaning data, and preparing features

• 🤖 PyCaret (AutoML) – To train and tune machine learning churn models with minimal code

• 🔄 BigQuery Export – Push model predictions back into the warehouse for reporting

• 📊 Looker Studio – Main platform for dashboard visualization and storytelling


4. Data Source

Source: HR Employee Dataset 

Link to Looker Report:
(https://lookerstudio.google.com/reporting/0eb8af6e-f026-4881-bce5-ca446060a857)

The dataset includes:

Employee demographics and department allocation

Work-related features: projects completed, average monthly hours, years at company

Performance indicators: satisfaction level, last evaluation scores

Outcomes: whether the employee stayed or left the company

5. Features / Highlights

Business Problem
High employee turnover increases recruitment costs, reduces team productivity, and impacts organizational culture. The company needs early detection of employees likely to leave.

Goal of the Dashboard
To give HR leaders a predictive tool for:

Monitoring overall churn percentage

Identifying high-risk employees and departments

Understanding the strongest drivers of attrition

Supporting evidence-based retention strategies

6. Walkthrough of Key Visuals

Top KPIs Panel

Churn Percentage: 7%

Satisfaction Level: 0.5 (avg)

Total Years at Company: 3.39

Last Evaluation: 0.47

Departments Analyzed: 10

Drivers of Churn (Bar Chart)
Highlights the most important features from the Random Forest model:

Satisfaction level (top driver)

Time spent at company

Number of projects

Average monthly hours

Last evaluation score

At-Risk Employees (KPI)

7 employees predicted to leave in the pilot program.

Department-Level Risk (Clustered Bar Chart)
Compares predicted to stay vs predicted to leave across functions (Technical, Support, Sales, Product Management, etc.)

7. Business Impact & Insights

📊 Satisfaction is the #1 Predictor: Employees with lower job satisfaction are at the highest risk of leaving.

🕒 Tenure and Workload Matter: Moderate tenure, balanced workloads, and fair evaluations reduce churn risk.

⚠️ Low Salary & Accidents Less Relevant: These features had minimal impact on churn, suggesting focus should shift elsewhere.

🎯 Actionable Retention Strategy: Insights highlight the need for programs improving job satisfaction, workload balance, and performance evaluation transparency.

💡 Proactive HR Intervention: Early identification of 7 high-risk employees allows targeted retention actions before attrition occurs.)
