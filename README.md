# Research-work-on-handling-imbalanced-data-set
In this study, we presented a liberal overview of the problem of handling imbalanced data sets with particular focus on performance measures and re-sampling methodologies. 
Although we proposed five (5) performance measures, we focused on F1-score and the AUC score in our reporting. 
The reason been that, these two measures represent the best performance measures when dealing with imbalance class data set. 
We also focused on the SMOTE and ADASYN re-sampling methodologies. 
We discussed that, compared to SMOTE, ADASYN put more focus on the minority samples that are difficult to learn by generating more synthetic data points for these difficult and hard to learn minority class samples. We also discussed that while SMOTE considers a  uniform weight in generating new synthetic data for all minority points, ADASYN considers a density distribution in deciding the number of synthetic samples to be generated for a
particular minority data point. 
In this study, while both SMOTE and ADASYN when applied to the imbalance class data set, 
in an improvement in the performance measures (F1-score and AUC score),
SMOTE generally reported higher scores than ADASYN. However, 
there are not enough evidence to generalize based on this study that, SMOTE performs better than ADASYN in handling class imbalance.
Factors not limited to the type of classifier, parameter tuning and the type of imbalance class data set can definitely affect 
the performances of SMOTE and ADASYN.
