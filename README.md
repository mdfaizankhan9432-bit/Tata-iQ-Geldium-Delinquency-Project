# Tata iQ - Geldium Credit Card Delinquency Project

A virtual work experience project from **Tata iQ on Forage**. I worked as a consultant for a made-up finance company, **Geldium Finance**. The case and data came from the program. This was not a real job.

## The problem

More and more Geldium customers were missing credit card payments by over 30 days. The collections team worked mostly by hand, so they reached customers too late. My job was to study the data, plan a way to predict who may miss a payment, and suggest what to do about it.

## What I did

**Task 1: Understanding the data**
The data had 500 customers, and 16% of them had missed payments. I found missing values, messy labels (six spellings for four employment groups) and units that did not match the guide. I fixed these with simple steps. I also noticed that payment history and credit score showed almost no link with delinquency, so I suggested Geldium confirm how these fields are defined.

**Task 2: Prediction plan**
I chose **logistic regression** because it is easy to explain to business people and customers. Since only 16% of customers are delinquent, I explained why accuracy alone is misleading and planned to use recall, precision, F1 and AUC, along with fairness checks.

**Task 3: Report for the Head of Collections**
I wrote a 2-page report in plain language. Early risk signals: unemployed customers (19.4% delinquent), Business card holders (21.3%) and higher credit utilization. The baseline model was weak (AUC about 0.5), so I did not overpromise. Instead I recommended a small **8-week pilot with a control group**, and wrote about fairness risks and human review.

**Task 4: Presentation**
A 6-slide deck on an AI-powered collections system: how it works, what AI does alone and what people must decide, safety rules for responsible AI, and expected impact (shown as pilot goals, not guarantees).

## Files

* `Task1_EDA_Report.pdf`
* `Task2_Model_Plan.pdf`
* `Task3_Business_Report.pdf`
* `Task4_AI_Collections_Strategy.pdf`
* `Certificate.pdf`

## What I learned

* Look closely at the data before building anything
* Accuracy can be misleading when one group is small
* In finance, a simple model people can understand is often better
* Fairness matters when a model affects people's money
* A small test is a safer first step than a big rollout

## Note

This was a virtual program on Forage. The dataset was provided by the program and is not included here. I added only the work I created myself.
