# Machine-Learning-Feature-Selection-and-Engineering
  Feature Selection and Engineering


The use of sklearn Feature Selection and Engineering to create  dataframe with the closing return (target variable), the previous day closing return, the previous 5-day rolling average closing return, and the previous 10-day rolling average closing return for every trading day from 01/01/2018 to 12/31/2019 for almost every stock in the S&P500 along with their sector classification. One-hot encoding was explored for the sector explanatory variable, but we felt aggregating the return variables on the sector variable was more appropriate for this exercise. The aggregation of the return variables on the sector variable not only accomplished the same goal as one-hot encoding by segregating each sector within the dataset, but it also serves as a measurement to how well that sector was performing throughout the dataset. The technique described, averaging a quantitative measurement on a categorical variable to encode the categorical variable, is known as mean encoding.



