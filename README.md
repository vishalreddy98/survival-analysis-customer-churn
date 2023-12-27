# Understanding Customer Churn with Survival Analysis

### Objective
Survival Analysis, as the name implies, uses statistics to estimate how long it will be
before a specific event, such as the failure of a mechanical component or a consumer
canceling their subscription, takes place. Although conventional regression techniques
successfully predict customer churn, they fail to give information about how long they
would stay with the company. We don’t want to discard this information as it’s valuable.

The main objective of this project is exploring different survival analysis methods and
performing telecommunication customer churn analysis. The report summarizes the
methodologies used and its results. We combined the traditional survival analysis
methods with the advanced survival analysis using machine learning techniques. In this
study, we investigated the non-parametric, parametric, and semi-parametric methods to
delineate the survival analysis algorithms and procedures. Different features in the data
which lead to churn are interpreted. The work presents experimental approaches to
enumerate the significance of survival analysis.

### Dataset Description
The data used in this project is publicly available online on multiple platforms. We
obtained it from Kaggle and studied using Python. The dataset contains information about
customers subscribed to a Telecom Service Provider.
Each row depicts a single customer uniquely identified by a customerID. The variables of
interest to us is ’tenure’ and ’Churn’. ’Tenure’ is a continuous variable and essentially
specifies how long (in months) the customer has stayed with the company.
’Churn’ is a categorical variable with two values where: Churn = ’Yes’ - the customer has
canceled subscription with the company Churn = ’No’ - the customer has been censored
(or) lost track of the customer.
Number of customers - 7043
Number of features - 21
