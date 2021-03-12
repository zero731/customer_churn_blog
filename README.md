# Investigating Customer Churn: A sample analysis
## Analysis of sample  data for Propheto blog

## Business Problem
This analysis and post were completed with the following situation in mind:<br><br>
You’re a general manager for a cellular provider. Your company sells cell phone plan subscriptions to customers in the United States. Looking through a report on your company’s performance last month, you immediately notice something troubling: you’ve signed thousands of new customers, but you’re falling short of revenue targets. <br>

You know that revenue is a composition of **new business**, **upsell**, and **churn**. A lack of new business doesn't appear to be the issue and upsell is of less immediate concern. You decide to investigate **customer churn**, the loss of customers using your product or subscribing to your services.

## Blog Post
A detailed description of the overall process and results of the analysis can be found in [this post](https://propheto.medium.com/demystifying-data-science-a-case-study-on-customer-churn-4bd90f5ae977).

## Repository Guide

```
├── Data                                            # Data folder
├── Figures                                         # Folder containing data visualizations
├── Other_notebooks                                 # Folder containing initial notebook
├── Customer_churn_analysis_Final.ipynb             # Main Jupyter notebook, contains analysis
├── README.md                                  
└── requirements.txt                                # Packages required to run code in notebook

```

## Reproduction Instructions

This project uses:

- [Anaconda](https://www.anaconda.com/), a package and environment management tool
- Python 3.7, along with the packages/libraries found in the [requirements.txt](https://github.com/zero731/customer_churn_blog/blob/main/requirements.txt) file

If you would like to follow the analysis locally and have the above tools:

1. Fork and clone this repository
2. In your terminal, navigate to the directory where you cloned this repository and run the following:

`pip install -r requirements.txt`

You should then be able to run the exploration and analysis in the provided [Customer_churn_analysis_Final Jupyter Notebook](https://github.com/zero731/customer_churn_blog/blob/main/Customer_churn_analysis_Final.ipynb).
