# Customer Churn Analysis for Telecommunication Company
Welcome to a transformative machine learning endeavor focused on binary classification within the Telco industry. This project delves into the Zanzibar telecommunication customer datasets, with the primary goal of amplifying profitability and revenue margins through enhanced customer retention strategies. Our journey entails harnessing the power of machine learning classification models to conduct in-depth churn analysis among the customer base. Guiding us through this exploration is the revered CRISP-DM Framework, lending structure and insights to every stage of our endeavor.

## Libraries to install 
We pip install and import libraries:
* For data manipulation and cleaning
* For data visualizations
* For Statistical testing
* For Feature Engineering & ML modeling
* Other supporting libraries to access SQL Server database, hide warnings.
  
## Columns

Gender -- Whether the customer is a male or a female

SeniorCitizen -- Whether a customer is a senior citizen or not

Partner -- Whether the customer has a partner or not (Yes, No)

Dependents -- Whether the customer has dependents or not (Yes, No)

Tenure -- Number of months the customer has stayed with the company

Phone Service -- Whether the customer has a phone service or not (Yes, No)

MultipleLines -- Whether the customer has multiple lines or not

InternetService -- Customer's internet service provider (DSL, Fiber Optic, No)

OnlineSecurity -- Whether the customer has online security or not (Yes, No, No Internet)

OnlineBackup -- Whether the customer has online backup or not (Yes, No, No Internet)

DeviceProtection -- Whether the customer has device protection or not (Yes, No, No internet service)

TechSupport -- Whether the customer has tech support or not (Yes, No, No internet)

StreamingTV -- Whether the customer has streaming TV or not (Yes, No, No internet service)

StreamingMovies -- Whether the customer has streaming movies or not (Yes, No, No Internet service)

Contract -- The contract term of the customer (Month-to-Month, One year, Two year)

PaperlessBilling -- Whether the customer has paperless billing or not (Yes, No)

Payment Method -- The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))

MonthlyCharges -- The amount charged to the customer monthly

TotalCharges -- The total amount charged to the customer

Churn -- Whether the customer churned or not (Yes or No)

## Hypothesis
H0(null):
The churning potential (likelihood of churn) among non-senior citizens is not influenced by factors such as Gender, internet service type, Payment method, Contract, monthly charges, tenure, and the presence of additional services like online security or tech support.

H1(alternate):
The churning potential (likelihood of churn) among non-senior citizens is influenced by factors such as Gender, internet service type, Payment method, Contract, monthly charges, tenure, and the presence of additional services like online security or tech support.

## Outcome
The statistical analysis shows that several factors significantly impact customer churn in the telecom company. The Chi-Square tests on categorical variables—like gender, internet services, payment method, contract term, and additional services—confirm their substantial influence on churn potential, as indicated by their p-values. These factors should be addressed to enhance customer satisfaction and loyalty, although the p-values are higher than the conventional threshold of 0.05. This leads to the rejection of the null hypothesis in favor of the alternate one, underscoring their impact on churn.

On the contrary, ANOVA tests reveal that two continuous variables, monthly charges and tenure, lack a statistically significant effect on customer attrition. With p-values below 0.05, the null hypothesis can reasonably be accepted in this regard. 

For modeling, models consistently identify true positives (TP) and true negatives (TN) while generating false positives (FP) and false negatives (FN), impacting overall accuracy for the unbalanced data. When data is balanced through techniques like SMOTE, models turn to prioritize the minority class ('Churn: Yes') for improved sensitivity, however model assessment requires metrics like accuracy, precision, recall, and F1-score on an independent validation set. Among models, the Random Forest Classifier excels in cross-validation accuracy for balanced data, with Gradient Boosting Classifier closely following. Model selection depends on priorities, considering SVC's true positive count or Gradient Boosting's balanced F1-score, requiring rigorous metric evaluation and problem-specific analysis

## Recommendations
1. Tailored Strategies for Different Groups
2. Prioritize Customer Satisfaction
3. Keep Pricing Competitive
4. Reward Loyalty for Long-Term Customers
5. Stay Customer-Centric with Data
   
## Conclusion
Based on these results, it's crucial to introduce customized approaches for various segments, emphasize satisfaction, ensure competitive pricing, establish loyalty programs, provide personalized assistance for new customers, and adopt data-driven improvements that revolve around customer needs. These actions are essential to bolster customer loyalty and fine-tune the company's overall strategy.

## Authors
| Name | GitHub link |
| ---- | ---- |
| Doe Edinam                   | https://github.com/doeabla         |
| Kofi Asare Bamfo             | https://github.com/akbamfo         |
| Enoch Taylor-Nketiah         | https://github.com/kojoboyoo       |
| Timothy Morenikeji Akinremi  | https://github.com/timothyakinremi |

follow me on linkedin - https://www.linkedin.com/pulse/indian-startup-ecosystem-enoch-taylor-nketiah%3FtrackingId=jCEVr7E12p377%252BgWF0WLxA%253D%253D/?trackingId=jCEVr7E12p377%2BgWF0WLxA%3D%3D


