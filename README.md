# R_creditcard.github.io
Team members:
Rui Cheng(rc3372), Guoshiwen Han(gh2567), Shiyun Yang (sy2797)

This project is to reproduce the paper “The Comparisons of Data Mining Techniques for The Predictive Accuracy of Probability of Default of Credit Card Clients”, based on the dataset “Default of Credit Card Clients Dataset”. Then propose and implement the additional methods that are not included in the paper to better predict the result.

The paper includes six statistical learning models to predict the default probability of credit card holders and evaluate the performance of the six models, KNN, LR, discriminant analysis, naive Bayesian classifier, ANNs, and classification trees. It compares the accuracy of the prediction of the default probabilities, using error rate, area ratio, coefficient, intercept, and R2 of its proposed Sorting Smoothing Method as its performance metrics. Among the six techniques, the Artificial Neural Networks model has the best accuracy giving the prediction of default probability.

Besides, we implemented Principal Component Analysis to preprocess the data, and Support Vector Machines, Deep Neural Network, and Random Forest to predict the probability.

All method implementations are done in R language.

paper:
https://bradzzz.gitbooks.io/ga-dsi-seattle/content/dsi/dsi_05_classification_databases/2.1-lesson/assets/datasets/DefaultCreditCardClients_yeh_2009.pdf

dataset:
https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
