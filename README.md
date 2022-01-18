# Customer-Retention-Model-for-Telecom-Domain

Develop a predictive framework for enabling proactive retention stategy for a telecom company.

Customer Lifecycle: Acquisations,Early Engagement Cross sell and business growth and Customer Retention.

POC helps in an area of Customer Rentention and created as strategy which type of customer will likely to attrites.

Our POC will help in 3 different area which is ATP.

Audience:- who should be targeted using the model.
Treatment:- identify the area where the offers can be made.
Prioritization:- Determine an order of priority for smooth execution.

Baseline Event Rate:

The Response Rate from the data is 26.5%.

Algorithms Used :

In this project we have used Logistic Regression, Decision Trees, Random Forests,Gradient Boosting Algorithms,Stack Classifier.

Final Model Algorithm:

Among the models that we tried building the GBM Algorithm performed best.

Grid Search CV parameters:

Maximum Depth of Tree - 6

Minimum Sample Size for Nodes to be Split - 50 Observations.

Model Performance Measures:

Accuracy - 0.79

Precision - 0.64

Recall - 0.52

F1 Score - 0.57.

Top 10 drivers from the Model:

tenure	0.207963

TotalCharges	0.185813

MonthlyCharges	0.166751

PaymentMethod_Electronic check	0.137275

InternetService_Fiber optic	0.133763

Contract_Two year	0.036155

Contract_One year	0.033409

PaperlessBilling_Yes	0.019680

OnlineSecurity_Yes	0.014681

TechSupport_Yes	0.013139

SeniorCitizen	0.011829

Solution:

1.Device Protection with Online Services.
2.Convert customer to DSL if they are facing challenges with fibre optics.
3.Offer Discounts on Yearly Contract.
