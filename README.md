# Credit_Risk_Analysis
Analysis of  German Credit risk data using ML algorithms
We have used the german credit data available on the kaggle platform for this analysis.
First , we divide our borrowers into different groups based on riskiness through k means clustering.In order to find our sufficient number of clusters, we first apply elbow method followed by the sillhouette score method and the well known CH method.
Then we applied a well known parametric model, logistic regression, to the german credit risk data.
The performance of logistic regression was then compared with Bayesian estimation based on MAP and MH.
Finally, coremachine learning models- namely SVC, Random forest and Neural Networks with deep learning were employed and the performance of the models was compared by calculating their ROC-AUC  score.
