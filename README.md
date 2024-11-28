# Health Insurance Analytics Project
<center><img width="40%" src="https://img.freepik.com/free-vector/social-security-concept-illustration_114360-17279.jpg?t=st=1731539901~exp=1731543501~hmac=f2cec6918cf5f73b2fabc8333bffb8216ee41c5c08ac1326536af5fd3c35c89b&w=1380"></center>

Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.

## Business Problem

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

**VARIABLES**

* `id`:   Unique ID for the customer
* `Gender`:   Gender of the customer
* `Age`:	Age of the customer
* `Driving_License`:	0 : Customer does not have DL, 1 : Customer already has DL
* `Region_Code`:	Unique code for the region of the customer
* `Previously_Insured`:	1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance
* `Vehicle_Age`:	Age of the Vehicle
* `Vehicle_Damage`:	1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.
* `Annual_Premium`:	The amount customer needs to pay as premium in the year
* `Policy_Sales_Channel`: Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.
* `Vintage`:	Number of Days, Customer has been associated with the company
* `Response`:	1 : Customer is interested, 0 : Customer is not interested

ASSUMPTION : The response  = 0, means that the response was a negative and not a non response.

## Methodology

The project was structured in analysis cycles to ensure progressive deep dives into the data and hypotheses. In the first cycle, the focus was on exploring the provided dataset, identifying potential correlations, and testing preliminary hypotheses.

Steps:

	1.	Initial data exploration:
	2.	Checking for missing values.
	3.	Descriptive statistics to understand data distribution.
	4.	Hypothesis formulation
	5.	Hypothesis validation
 
## Hypothesis
* **H1** - Younger customers may be more likely to purchase car insurance due to a higher probability of buying their first car or being interested in newer models that require insurance.
* **H2** - Men may show greater interest in car insurance compared to women, possibly due to a cultural association with driving.
* **H3** -  Customers in urban areas or with higher population density may be more prone to purchasing car insurance due to the greater need for transportation and increased risk of accidents.
* **H4** - Customers who already have health insurance and also own a vehicle are more likely to purchase car insurance.
* **H5** - Long-time customers with a good payment history may be more likely to purchase another product from the insurer, such as car insurance.
* **H6** - Customers who purchased health insurance through a specific channel (online, phone, agent) may be more likely to purchase car insurance through the same channel.

Key Insights:

	•	Preventive health policies: Develop campaigns focused on weight control and smoking cessation programs to reduce costs.
	•	Personalized pricing: Adjust prices based on risk profiles, considering factors like age, BMI, and smoking habits.
	•	Regional focus: Investigate what makes certain regions more expensive and implement solutions to mitigate costs.

## Tools and Technologies

	•	Programming Language: Python
	•	Key Libraries: pandas, numpy, matplotlib, seaborn
	•	Tools: Jupyter Notebook

## Next Steps

	•	Refine analysis models with machine learning techniques to predict costs for new customers.
	•	Conduct additional tests to verify hypotheses related to behavior and medical history.
	•	Create interactive dashboards to communicate insights to the company’s stakeholders.

