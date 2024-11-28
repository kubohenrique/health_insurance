# Health Insurance Analytics Project

Project Overview

This project aims to assist a health insurance company in understanding the main factors that influence the costs of health insurance plans. Using historical data, we applied exploratory data analysis techniques to identify patterns, formulate hypotheses, and extract insights that guide strategic decisions.

Business Problem

The company faces the challenge of determining the key factors that impact health insurance costs for its customers. These factors may range from demographic characteristics to health-related conditions, such as body mass index (BMI) and family medical history. The main goals are:
	1.	Reducing operational costs by adjusting internal policies.
	2.	Developing more accurate and fair pricing strategies for new and existing customers.
	3.	Predicting the impact of future changes in the customer portfolio.

Methodology

The project was structured in analysis cycles to ensure progressive deep dives into the data and hypotheses. In the first cycle, the focus was on exploring the provided dataset, identifying potential correlations, and testing preliminary hypotheses.

Steps:

	1.	Initial data exploration:
	•	Checking for missing values.
	•	Descriptive statistics to understand data distribution.
	2.	Hypothesis formulation:
Hypotheses were generated based on characteristics such as age, BMI, number of dependents, smoking habits, and geographical region.
	3.	Hypothesis validation:
Statistical techniques and visualizations were used to identify trends and test whether the hypotheses were supported by the data.

Insights and Results from Cycle 01

Hypotheses Raised:

	1.	Age and cost: Older customers tend to generate higher costs.
	•	Result: Confirmed. A positive correlation was found between age and costs.
	2.	BMI and cost: Individuals with higher BMI incur greater costs due to higher health risks.
	•	Result: Confirmed. BMI showed a strong correlation with increased costs.
	3.	Smoking and cost: Smokers have higher medical costs compared to non-smokers.
	•	Result: Confirmed. Smokers displayed significantly higher costs.
	4.	Geographical region and cost: Regional differences impact costs due to local policies and medical infrastructure.
	•	Result: Partially confirmed. Certain regions showed significant cost discrepancies, while others did not.

Key Insights:

	•	Preventive health policies: Develop campaigns focused on weight control and smoking cessation programs to reduce costs.
	•	Personalized pricing: Adjust prices based on risk profiles, considering factors like age, BMI, and smoking habits.
	•	Regional focus: Investigate what makes certain regions more expensive and implement solutions to mitigate costs.

Tools and Technologies

	•	Programming Language: Python
	•	Key Libraries: pandas, numpy, matplotlib, seaborn
	•	Tools: Jupyter Notebook

Next Steps

	•	Refine analysis models with machine learning techniques to predict costs for new customers.
	•	Conduct additional tests to verify hypotheses related to behavior and medical history.
	•	Create interactive dashboards to communicate insights to the company’s stakeholders.

How to Run

	1.	Clone this repository:

git clone https://github.com/kubohenrique/health_insurance.git


	2.	Navigate to the project directory:

cd health_insurance


	3.	Install the required dependencies:

pip install -r requirements.txt


	4.	Run the notebooks in the Notebooks folder.

Author

Henrique Yukio Kubo
LinkedIn: Your Profile
GitHub: kubohenrique

Let me know if you’d like further refinements! 😊
