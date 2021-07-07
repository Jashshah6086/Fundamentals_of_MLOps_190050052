Part1

Question 1
What is AIOps?
AIOps is a series of multi-layered platforms that automate IT to make it more efficient. Gartner coined the term in 2017, which emphasizes how new this discipline is. (Disclosure: I worked for Gartner for four years.)At its best, AIOps allows teams to improve their IT infrastructure by using big data, advanced analytics, and machine learning techniques. That first item is crucial given the mammoth amount of data produced today.When it comes to data, more isn't always better. In fact, many business leaders say they receive so much data that it's increasingly hard for them to collect, clean, and analyze it to find insights that can help their businesses.This is where AIOps comes in. By helping DevOps and data operations (DataOps) teams choose what to automate, from development to production, this discipline helps open source teams predict performance problems, do root cause analysis, find anomalies, and more.

What is MLOps?
MLOps is a multidisciplinary approach to managing machine learning algorithms as ongoing products, each with its own continuous lifecycle. It's a discipline that aims to build, scale, and deploy algorithms to production consistently.Think of MLOps as DevOps applied to machine learning pipelines. It's a collaboration between data scientists, data engineers, and operations teams. Done well, it gives members of all teams more shared clarity on machine learning projects.MLOps has obvious benefits for data science and data engineering teams. Since members of both teams sometimes work in silos, using shared infrastructure boosts transparency.But MLOps can benefit other colleagues, too. This discipline offers the ops side more autonomy over regulation.As an increasing number of businesses start using machine learning, they'll come under more scrutiny from the government, media, and public. This is especially true of machine learning in highly regulated industries like healthcare, finance, and autonomous vehicles.Still skeptical? Consider that just 13% of data science projects make it to production. The reasons are outside this article's scope. But, like AIOps helps teams automate their tech lifecycles, MLOps helps teams choose which tools, techniques, and documentation will help their models reach production.

Source : https://opensource.com/article/21/2/aiops-vs-mlops

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Question 2

A machine learning model is interpretable if we can fundamentally understand how it arrived at a specific decision. A model is explainable if we can understand how a specific node in a complex model technically influences the output.

Interpretation of a Numerical Feature
An increase of feature xk by one unit increases the prediction for y by βk units when all other feature values remain fixed.

Another important measurement for interpreting linear models is the R-squared measurement. R-squared tells you how much of the total variance of your target outcome is explained by the model. The higher R-squared, the better your model explains the data.The SSE tells you how much variance remains after fitting the linear model, which is measured by the squared differences between the predicted and actual target values. SST is the total variance of the target outcome. R-squared tells you how much of your variance can be explained by the linear model. R-squared ranges between 0 for models where the model does not explain the data at all and 1 for models that explain all of the variance in your data.It is better to use the adjusted R-squared, which accounts for the number of features used in the model.It is not meaningful to interpret a model with very low (adjusted) R-squared, because such a model basically does not explain much of the variance. Any interpretation of the weights would not be meaningful.

The importance of a feature in a linear regression model can be measured by the absolute value of its t-statistic or p-value.

Source : https://christophm.github.io/interpretable-ml-book/limo.html

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
