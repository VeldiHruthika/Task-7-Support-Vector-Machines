Task 7: Support Vector Machines (SVM)

-Hey! This was my seventh task, where I learned how to use SVM (Support Vector Machines) for linear and non-linear classification.

-I used the Breast Cancer dataset which is a binary classification problem — predicting whether a tumor is malignant or benign based on medical measurements.

What I did in this task:
1.Loaded the Breast Cancer dataset from Scikit-learn.
It had 30 features like radius, texture, smoothness, etc.

2.Standardized all the features using StandardScaler — because SVMs work best with normalized data.

3.Split the data into training and test sets (80% train, 20% test).

4.Trained an SVM with a linear kernel:

i.Tested it on the test set.

ii.Got high accuracy.

iii.Printed classification report and confusion matrix.

5.Trained another SVM with RBF (Gaussian) kernel:

i.This handles non-linear decision boundaries.

ii.Again got strong performance.

6.Visualized the decision boundary using PCA (2D projection):

i.Reduced 30 features to just 2 using PCA.

ii.Trained a 2D SVM model and plotted the decision regions.

iii.Used matplotlib for a clear visual of how classes are separated.

7.Tuned hyperparameters using GridSearchCV:

i.Tried different combinations of C (regularization) and gamma (kernel sensitivity).

ii.Found the best combination for max accuracy.

8.Evaluated the best SVM model using Cross-Validation:

i.Used 5-fold cross-validation.

ii.Reported all 5 scores and mean CV accuracy.

