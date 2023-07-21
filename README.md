# Customer Churn, Lifetime Value, and Satisfaction Analysis

## Table of Contents
- [About](#about)
    - [Information About The Dataset](#information-about-the-dataset)
- [Prerequisites](#prerequisites)
- [Results](#results)
- [Future Steps](#future-steps)
- [Contact](#contact)

## About
This project employs advanced data analytics techniques to analyze customer churn, lifetime value, and satisfaction. The objectives of this project are:

1. **Customer Churn Analysis**: The project aims to identify the factors contributing to customer churn and develop predictive models to identify customers at risk of churning. 

2. **Customer Lifetime Value (CLV) Analysis**: The analysis seeks to estimate the monetary value attributed to the future relationship with a customer, helping to guide business decisions and strategy.

3. **Customer Satisfaction Analysis**: By analyzing customer feedback and other relevant data, the project strives to understand the factors contributing to customer satisfaction and how it impacts the churn rate and CLV.

To run the project, you can explore any of the following notebooks based on your interests. Each notebook stands on its own and can be run independently, offering insights into different aspects of the data.

1. `Customer_Churn.ipynb`: Analyzes customer churn & develops a predictive model.
2. `Customer_LTV_Analysis.ipynb`: Analyzes customer lifetime value.
3. `Customer Satisfaction Analysis.ipynb`: Investigates the factors influencing customer satisfaction.

In addition to the above, we are in the process of developing a fourth notebook: `Unified_Insights.ipynb`. This notebook will synthesize insights from the other three notebooks to provide a comprehensive understanding of customer behavior.

It will follow this logical flow:

1. Insights from customer satisfaction analysis.
2. Connecting customer satisfaction to churn rates.
3. The impact of churn rates on customer lifetime value.
4. Overall recommendations and strategies based on these findings.

Please note that `Unified_Insights.ipynb` is a work in progress and will be added to the repository upon completion.


### Information About The Dataset
The project makes use of the **Telco Customer Churn dataset** available at [IBM Business Analytics Community](https://accelerator.ca.analytics.ibm.com/bi/?perspective=authoring&pathRef=.public_folders%2FIBM%2BAccelerator%2BCatalog%2FContent%2FDAT00148&id=i9710CF25EF75468D95FFFC7D57D45204&objRef=i9710CF25EF75468D95FFFC7D57D45204&action=run&format=HTML&cmPropStr=%7B%22id%22%3A%22i9710CF25EF75468D95FFFC7D57D45204%22%2C%22type%22%3A%22reportView%22%2C%22defaultName%22%3A%22DAT00148%22%2C%22permissions%22%3A%5B%22execute%22%2C%22read%22%2C%22traverse%22%5D%7D). The [data dictionary](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113) provides a detailed description of each field in the dataset.

## Prerequisites
To run this project, the following packages need to be installed. You can install them using pip:

```sh
pip install pandas matplotlib seaborn numpy scikit-learn statsmodels imbalanced-learn
```

## Results
-

Getting Started
Clone this repository to your local machine.
Set up a virtual environment and install the required dependencies using pip.
Run the notebooks in the order specified above. Note: Make sure to update the file paths in the notebooks if necessary.

## Future Steps
-
