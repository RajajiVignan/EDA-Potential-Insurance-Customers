# EDA-Potential-Insurance-Customers

## About Data
  The Dataset is about the potential Insurance Buyers. The purpose of this project is to predict whether a person is willing to buy or not. The dataset is made possible with the resources provided in a Hack-a-thon (Analytics Vidya). Thanks to them for the opportunity.
  
  More info about the data is found in data.md
  

## Initial plan for Data Exploration:
1. Removing the unnecessary features first.
2. Replacing the null values and Data cleaning.
3. Data wrangling: mean, std, max and, also correlation
4. Univariate analysis: to understand single feature precisely.
5. Bi-variate and Multi-variate analysis: for drawing out insights, inferences.

## Data Exploration

### Univariate Analysis:
<p> Understanding the Recovered Insurance types. By the count plot, it's clear that there are more individual account in the dataset.</p>
<img src="/images/1.png" alt="drawing" width="400" height="300"/>

<br>

<p>After that, it is necessary to analyze the distribution of the customers among the cities mentioned with the help of a seaborn countplot.</p>
<img src="/images/2.png" alt="drawing" width="700" height="400"/>

<br>

<p> In the process, the distribution of the policy premium recovered so far is found out to be right skewed.</p>
<img src="/images/3.png" alt="drawing" width="400" height="300" />
<br>

### Multi-variate Analysis
<p> Explored the the policy type and their percentages at which the customers bought while comparing them whether the customer is individual or joint account holder</p>
<img src="/images/4.png" alt="drawing" width="600" height="400"/>
<br>

<p> Also, found out the goldilock zone of the duration of policy holders to buy another policy. </p>
<img src="/images/5.png" alt="drawing" width="700" height="400"/>
<br>

<p> A compilation of different plots using seaborn pair plots </p>
<img src="/images/6.png" alt="drawing" width="800" height="700"/>


The detailed insights from EDA is mentioned in the notebook.
