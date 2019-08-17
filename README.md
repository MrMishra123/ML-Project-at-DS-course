# Credit Risk Analysis( Group Project )
A short primer of underwriting in the credit industry - 
In general, whenever an individual/corporation applies for a loan from a bank (or any loan issuer), their credit history undergoes a rigorous check to ensure that whether they are capable enough to pay off the loan (in this industry it is referred to as credit-worthiness). 

## Overview
In this project we will have to put ourself in the shoes of a loan issuer and manage credit risk by using the past data and deciding whom to give the loan to in the future. The text files contain complete loan data for all loans issued by XYZ Corp. through 2007-2015. The data contains the indicator of default, payment information, credit history, etc.

The data should be divided into train (June 2007 - May 2015) and out-of-time test (June 2015 - Dec 2015) data. We will have to use the training data to build models/analytical solution and finally apply it to test data to measure the performance and robustness of the models. 

## Objective 
We have to build a data model to predict the probability of default, and choose a cut-off based on what we feel is suitable. Alternatively we can also use a modelling technique which gives binary output. We have to do the following:

Based on the data that is available during loan application, build a model to predict default in the future. This will help the company in deciding whether or not to pass the loan.

Also note that the data contains defaulters, successful payers and customers who were current during that time. To simplify the problem, customers under 'current' status have been considered as non-defaulters in the dataset.
