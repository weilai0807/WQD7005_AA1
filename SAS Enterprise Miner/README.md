# Performance Comparison - Decision Tree 
From the performance result, we can see that Decision Tree – Max levels has the least misclassification rate in validation, followed by Decision Tree – 3 levels and Decision Tree – 2 levels. This could be due to the data contains complex patterns that are better captured by a deeper decision tree. Furthermore, there are not much difference between valid misclassification rate and train misclassification rate, indicating the model did not encounter overfitting. A deeper decision tree can generalize well in large dataset, resulting lower misclassification rate.  

From the feature importance figure, we can see that Tenure has the highest impact to whether the customer will churn or not. The higher the tenure, the lower the probability that the customer will churn. Apart from that, complain is the second variable that impact whether the customer will churn or not. High complains results in customer’s churn. The figure also showed the variables such as NumberOfAddress, CashbackAmount, PreferredPaymentMode, PreferredOrderCat and more that will impact to whether the customer will churn or not.