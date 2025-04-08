# python_final_project


The task is to find the R-peaks, so that we can divide a long ECG signal
into individual heart beats.

• A by-product: we can use the R-peaks to calculate heart rate 
- The ECG signals have been divided into individual beats

- Build four classifiers to classifier the ECG signals into 5 classes, using the default parameter values
for each classifier.
• KNeighborsClassifier
• LogisticRegression
• DecisionTreeClassifier
• RandomForestClassifier
• Report the training accuracy and the test accuracy in a Table (pandas dataframe


Then, Build three classifiers to classifier the ECG signals into 5 classes, and find the optimal value of the
parameter for each classifier by using five fold cross-validation (GridSearchCV).
• KNeighborsClassifier (n_neighbors)
• DecisionTreeClassifier(max_depth)
• RandomForestClassifier(max_depth)
