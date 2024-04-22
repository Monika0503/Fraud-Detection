# Fraud-Detection

• The goal of this project is to predict the potentially fraudulent providers based on the claims filed by them.
• To discover important variables helpful in detecting the behaviour of potentially fraud providers.
• To Study fraudulent patterns in the provider’s claims to understand the future behaviour of providers
• Financial loss is a great concern, but also protecting the healthcare sys- tem so that they can provide quality and safe care to legitimate patients.

Conclusions:

• We saw that Markov model with GBM and Random forest worked the best model for this healthcare provider fraud detection project.
• We can conclude that when machine learning model is incorporated into some of statistical models (Markov model) we can except a significant improvement in the performance.
• Markov Model shows a significant improvement when a boosting tech- nique is used and hence,gave us Specificity of 98.32% which means that it
is correctly predicting 98.32% of non-fraudulent claims as non-fraudulent which,thus takes care of minimising Type 2 error also. Moreover,Accuracy is 83% which is also considerably good.
• Also, random forest gave us Area under Curve of 0.96 which implies that the model achieves a high TPR while maintaining a low FPR. In other words, it has a high probability of correctly identifying fraud cases (true positives) while minimizing false alarms (false positives).With an AUC of 0.96, the model demonstrates a high level of discrimination power. It indicates that the model has a strong ability to correctly rank and differentiate between fraudulent and non-fraudulent cases across a range 63 64 of classification thresholds.
• But Markov model with GBM is more interpretable than random forest as random forest is a Black-Box model.
• We have considered to use time homogeneous Markov Model from our observation of EDA where we found out that Claim variable is Uniformly distributed.

