## Reference Link

- Random Forest Classifier + Feature Importance
https://www.kaggle.com/prashant111/random-forest-classifier-feature-importance
> In this project, I build a Random Forest Classifier to predict the income of a person. I build two models, one with 10 decision-trees and another one with 100 decision-trees.
The model accuracy score with 10 decision-trees is 0.8446 but the same with 100 decision-trees is 0.8521. So, as expected accuracy increases with number of decision-trees in the model.
I have used the Random Forest model to find only the important features, build the model using these features and see its effect on accuracy.
I have removed the native_country_41 variable from the model, rebuild it and checked its accuracy. The accuracy of the model with native_country_41 variable removed is 0.8544. So, we can see that the model accuracy has been improved with native_country_41 variable removed from the model.
Confusion matrix and classification report are another tool to visualize the model performance. They yield good performance.

- EDA + Logistic Regression + PCA
https://www.kaggle.com/prashant111/eda-logistic-regression-pca
> In this kernel, I have discussed Principal Component Analysis – the most popular dimensionality reduction technique.
I have demonstrated PCA implementation with Logistic Regression on the adult dataset.
I found the maximum accuracy with the first 12 features and it is found to be 0.8227.
As expected, the number of dimensions required to preserve 90 % of variance is found to be 12.
Finally, I plot the explained variance ratio with number of dimensions. The graph confirms that approximately 90% of variance is explained by the first 12 components.