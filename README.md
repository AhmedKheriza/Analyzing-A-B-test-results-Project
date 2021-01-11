# Analyzing-A-B-test-results-Project
## by (Ahmed Kheriza)

## Introduction

For this project, I will be working on an A/B test run by an e-commerce website. 
My goal is to work through this project to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Dataset

The dataset contains 294478 rows of data about the website users containing:
user_id,	timestamp,	group,	landing_page and	converted.
The dataset is provided.


## Summary of Findings

In Part I, In all model I failed to reject the null hypothesis because the p-value is higher alpha (P-value > Alpha) (First type error) Which means than the older page is equal or better than the new one (Null hypothesis).
In part II, I get the same results from Logistic regression model which means that we also can't reject the null hypothesis so that the older page is equal or better than the new one.
After adding country column in mind, I found that the country doesn't matter so much in conversion result.
