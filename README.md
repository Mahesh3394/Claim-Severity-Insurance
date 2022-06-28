# Claim_severity_Insurance

Basically this model can predict severity of claim in terms of loss. This will helpful for identify loss ratio and other important factors for company.

# Introduction

Insurance sector is growing sector in current world. Insurance market is on boom after post covid era. Various new players enetered in market making old players competitive environment. Thus it is very important to come up with new ideas to tackle competition. Here we developing automated methods of predicting the cost, and hence severity, of claims. This will help us to understand the severity of claim and cost to insurance company from claim.

# Business problem.

We are provided with a dataset which contains claim records of insurance company. A record contains both categorical and continuous features. The target feature is just the numerical loss that this claim caused. All the features are extremely anonymized: we don't either know the real names of the features or their true values.

This is clearly a regression problem where target is numerical value and we have to predict future loss by using given features. Also we already have target value in train data set so we can do supervised learning and train model on given data set.

As we can afford to take time to predict loss, there is no requirement of very low latency.
