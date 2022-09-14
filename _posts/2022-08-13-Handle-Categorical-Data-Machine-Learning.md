---
layout: post
title: "How to Handle Catgorical Data in Machine Learning"
---

Most of Machine Learning can't handle categorical data (either input or output), they expect data to be numerical.
That's why we need to encode the categorical data to numeric.

Before we jump into "How to encode?", we have to deal about what is actually categorical and numerical.
Numeric is anything of containing number and categorical is containing data that can identified based on label or group.
Categorical data divide into 2: Nominal value (there is no relationship amoung group) and ordinal value (can be rank)

Numerical data type example : 

        1,2,3,4.5

Categorical data : 

        1. Nominal : Men and Women
        2. Categorical : good,bad, enough

There is some popular way to do it:

1. Ordinal Encoding
2. Label Encoding
3. One-Hot Encoding
4. Frequency Encoding

Note : In this post, I refer to [my Telco-Customer-Churn-Behaviour project](https://github.com/rizqiamaliatuss/Customer_Churn_Prediction) in repository

Let's move it!

# 1. Label Encoding







