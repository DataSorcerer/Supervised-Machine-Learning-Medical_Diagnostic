# Supervised-Machine-Learning-Medical_Diagnostic   
   
   Since past few years, supervised machine learning techniques have been leveraged successfully for building highly accurate predictive models for medical diagnostic tests. In this experiment, I have explored the problem of predicting medical test outcome based on following features:
    - Plasma glucose level
	- Blood Pressure
	- Skin thickness
	- Number of pregnancies
	- Insulin
	- BMI
	- Age
	
	Outcome of the test: This is a binary classification problem, so we classify if test results RE positive/ negative. There are only a limited amount of training samples available (376). These are divided into train/ test and validation sets. The performance is evaluated over this held out (validation set), so that performance can be gauged over truly unseen data.

	Performance metrics used: 10 - fold stratified cross validation is performed and following performance metrics are computed:
	1. Confusion Matrix
	2. Accuracy
	3. Sensitivity
	4. Specificity
	5. ROC curves are examined