# Data-analysis

Analysing brfss_for_bda_2021.csv data set which describes a survey around
health and associated behavioural factors carried out on a population in the US.

### We stated the three research questions to answer through our analysis.

### Processing the data

We performed data exploration by

• Calculating metrics of data 

• Performing basic queries and aggregations 

• Visualizing data with plots

### Data cleaning

Missing values can be handled by removing null records, impute them with different 
values such as mean, median, mode and filling the records with special values.Also, for numerical columns, boxplots were used to check whether they consist of any outliers. Some of the columns which had outliers were imputed by means and median.

### Data analysis

The performance measurements, Accuracy, Recall and F1-Score was used to measure the model 
performance. Since our dataset target class was highly imbalanced, we used three 
sampling techniques to handle the imbalanced dataset. The over sampling technique, the 
under-sampling technique and the SMOTE approach was used to have a more balanced 
data. Finally, the Logistic Regression model was used to build the predicting model and to interpret the results.
Also the relationship was measured by analysing the Chi-squared value to find if the difference is due to randomness or a relationship between variables. 
