
# **Deep Dive Project - Group 10**

## Group Members:

1. Jayesh Yevale (jyeval2)
2. Ethan Torres (ethanjt2)
3. Joshua Kendrick (joshua39)
4. Dhruv Oza (dhruvo2)


## Project Title:

Analyzing and Predicting California's Unemployment Rate Using Deep Learning

## Problem Statement:

California, with its diverse economy and large population, faces ongoing challenges related to unemployment. Despite being home to the world’s leading tech companies, the parts of the State of California still faces and struggles with economic instability, high inflation, and poverty rates. There exists a need of reliable tools for goverment, policymakers and individuals to understand and anticipate changes in the job market scenarios for making appropriate and informed decisions. Additionally, recent fluctuations have exacerbated, like the COVID-19 pandemic, etc., making more critical than ever to understand and predict unemployment trends.

Our project aims to develop a model using deep learning, specifically Recurrent Neural Networks (RNNs), to predict California’s unemployment rate. By analyzing historical data and incorporating socio-economic factors, this project will provide detailed insights on how employment trends may evolve in the near future.

We expect to gain insights into both short-term and long-term unemployment trends. This model could help provide forecasts that are useful for state policymakers, allowing them to anticipate fluctuations in the labor market. In addition to this, the businesses and residents might benefit from understanding future trends to make better decisions regarding hiring, job searching, and relocation.

## Dataset Information:
### Source:

Local Area Unemployment Statistics for California dataset (https://data.ca.gov/dataset/59218446-5760-4683-b52e-f6210021840a/resource/b4bc4656-7866-420f-8d87-4eda4c9996ed/download/laborforceandunemployment_monthly_2024920.csv) which is made available by the California Open Data Portal (https://data.ca.gov/).

### Data Description:

For the above data source, we have the available data from January 1976 till August 2024, with total of 203,072 entries of employability data across various areas in California.

The dataset consists of total 12 columns, the major 6 features are Month, Year, Area, Total Labor Force, Employment, Unemployment, Area Type, along with the Label as Unemployment Rate.


## Milestones

### Milestone 0:
1. Form the project group and submit the URL of the selected project.

### Milestone 1:
1. Construct Google Folder.
2. Make a README file and stating a LICENSE.
3. Download data and prepare an extraction notebook with debudding and working datasets.
4. Convert these datasets to pandas, and pickle the data.

### Milestone 2:
1. Visualization of the data and some descriptive statistics including detailed description.
2. Discuss missing, imbalanced, or sparse data problems.
3. Prepare a Baseline learning notebook carrying, linear regression, ridge regression, and decision tree as benchmarks.

### Milestone 3:
1. Build a deep learning model for the dataset
2. Investigated effects of mini-batch learning
3. Investigated effects of different optimizers
4. Tuned hyperparameters (training testing and validation). 


### Milestone 4:
1. Perform Feature Importance using feature permutation and SHAPEY values on the best model from Milestone 3.
2. Discuss the importance of certain features in their ability to predict the unemployment rate in California.


### Milestone 5:
1. Documentation and cleanup of files.
2. Make Conclusions document for the entire project.
3. Conversion to repo.
4. Video summary of project. (Link: https://youtu.be/2SdIjJ6dkpY)
