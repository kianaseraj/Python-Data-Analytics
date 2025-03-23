**Churn Analysis – Who Stays, Who Leaves?**

- Dataset Overview

In this study we will predict customer churn within telecommunication industry, a sector characterized by intense competition and high customer turnover rates. The full cost of churn includes the loss of revenue from old churn and the marketing cost to replace them. Hence, analyzing use characteristics to avoid their loss and incerase their stickness has a huge revenue benefit for companys. 
Churn analysis is different from other customer analysis as it is more exploratory analysis and we are interested to find the causes rather than sales that are more evaluation based. In churn analysis we need to more focus on custoemrs' POV and get an understanding about market need.


By analyzing customer data and services they use we try to find a pattern in order to predict their churn and hence increasing their satisfaction, as a result of the researches, it has been determined that the cost of attracting new customers is 10 times more than the cost of holding existing customers. 

In this study feature selection, transformation and engineering has conducted and also algorithms such as logistic regreession and decision trees are testeed. 
Ensemble learnings outperfoms the single algorithms and stacking models provide the best result. 

The data we need must be: user potrait and behaviors, user consumptions!




1. Define churn:
It can be in a period of time frame not purchasing or ccancellign subscription or leaviing a negative comment. 
Data peprocessing; as in businesses such as telecommunication, banking, insurance they are subscrtioin based and we can consider customr churn as they leave the subscription. 

2. Data cleaning & preprocessing:
processing missing data, outliers, duplicates, normalizing the data, encoding categorical variables.

3. Feature selection:
retainnig rerlevant information such as servies usage, demogrraphic info such as age and gender, corr analysis

Establishing variables:
In order to have the balanced model, stratified sampling is applied according to a varibale such as age that the number of people in sub-group of churn variable is equal.

4. EDA:
finding patterns using visualization and descriptive statistics, examining the raltioinships of various features with each other and with churn variable.

5. Predictive model:
testing multiple algorithms and trying to find contributing features in dataset

6. Model evaluation with classificatoin metrics and the performance of the momdel is evaluated using the ML algorithms such as cox proportional hazard method and deep learning methods.


During predictoin it is tried to continuesly improve the model architecture and remove the features with low correlation values.


By analysing the services customers use their characteristics and billing information we try to predict which customers are prone to churn. 

The result shows that boosting techniques, which are non-paramteric, provide superior estimates. Also when the custoemr churn ate is lower it shows that logistic regression can be useful. In cases where churn is less, logistic rregressiion can be a good choice.







The questions we want to answer:

A. What customer behaviors are most associated with churn?

B. Do service features like tech support or online backup impact churn?

C. Which customer groups overpay compared to expected charges (charge_diff)?(tenuer segment with charge diff)

D. Does the number of subscribed services (NumServices) correlate with retention?

E. What is the impact of billing methods on retention, contract type and payment methods

F. Are there differences in churn rates between customers with and without dependents?


A.
<p align="center">
  <img src="pics/tenure_monthly_charges.jpg" alt="Tenure vs Monthly Charges" width="380" height="400">
  <img src="pics/tenure_segment.jpg" alt="Tenure Segments" width="380" height="400">
</p>


D.
<p align="center">
  <img src="pics/num_services.jpg" alt="Number of Services vs Dependency" width="380" height="400">
</p>


E. 
<p align="center">
  <img src="pics/contract.jpg" alt="Contract vs Tenure" width="380" height="400">
  <img src="pics/payment.jpg" alt="Payment vs Tenure" width="380" height="400">
  <img src="pics/payment.jpg" alt="Paper Billing vs Tenure" width="380" height="400">
</p>

F. 
<p align="center">
  <img src="pics/dependent.jpg" alt="Tenure vs Dependency" width="380" height="400">
</p>
