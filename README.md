**TITLE**

Diabities prdiction through Machine Learning

Diabetes Classification Using Machine Learning Diabetes classification involves predicting whether an individual has diabetes based on various medical attributes. This process is vital for early diagnosis and management, ultimately helping in reducing the health risks associated with diabetes. The classification model utilizes attributes such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, age, and the outcome (presence or absence of diabetes).

**SCORES**

**Logistic Regression:**

Achieved an accuracy of 78% on the training set and 77% on the testing set.
Shows a good balance between precision and recall for both classes.

**Decision Tree Classifier:**

Achieved perfect accuracy (100%) on the training set, indicating potential overfitting.
Performance on the testing set is lower (73%), suggesting overfitting to the training data.
Random Forest Classifier:

Achieved an accuracy of 100% on the training set, also indicating potential overfitting.
Performed better on the testing set (81%) compared to Decision Tree, suggesting better generalization.

**Support Vector Classifier (SVC):**

Achieved an accuracy of 81% on the training set and 79% on the testing set.
Shows a good balance between precision and recall for both classes.

**Overall:**

Random Forest Classifier shows the best performance on the testing set, indicating its ability to generalize well.
Decision Tree Classifier shows signs of overfitting, which needs to be addressed through techniques like pruning or limiting tree depth.
Logistic Regression and SVC provide decent performance with a good balance between precision and recall.



**CONCLUSION**

In this project, we tackled the challenge of diabetes classification using machine learning techniques. We explored various algorithms, including Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM), to predict whether an individual has diabetes based on medical attributes.

Through rigorous data preprocessing, exploratory data analysis, and model evaluation, we identified the most effective model for this specific dataset.

The chosen model demonstrated promising results in terms of accuracy, precision, recall, and F1-score, indicating its potential for real-world application in assisting healthcare professionals with early diabetes diagnosis.
