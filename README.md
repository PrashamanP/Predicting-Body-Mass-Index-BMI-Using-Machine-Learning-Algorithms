# Predicting-Body-Mass-Index-BMI-Using-Machine-Learning-Algorithms

# Objectives

This study looked into the validity and precision of employing different machine learning methods to classify BMI.

•	Comprehend the dataset.

•	Create classification models for predicting various BMI categories. 

•	Additionally, tune the hyperparameters and compare the assessment metrics of different classification methods.

# Methods
## Data collection method and dataset
Our dataset is taken from the Kaggle website data that was used in an obesity and overweight research. It contains data on the Body Mass Index (BMI) of individuals, along with other relevant features such as age, height, and weight.

The dataset consists of 500 samples and has been preprocessed to remove any missing values.

The dataset includes the following features:

i. Gender: the gender of the individual (male or female)

ii. Height: the height of the individual in meters
   
iii. Weight: the weight of the individual in kilograms

iv. Age: the age of the individual in years

v. BMI: the Body Mass Index of the individual, which is calculated as weight divided by height
squared (kg/m2)

vi. Absenteeism time in hours: the number of hours the individual was absent from work due to
a medical issue.

The aim of the dataset is to predict an individual's BMI based on the other features provided. The dataset has been preprocessed to remove any missing values and ensure that it is ready for machine learning algorithms.

This dataset can be used to explore the relationship between the different features and BMI, as well as to build machine learning models to predict BMI. The dataset has been used in the project to compare the performance of various machine learning algorithms. The aim of the dataset is to predict an individual's BMI based on the other features provided. The dataset has been preprocessed to remove any missing values and ensure that it is ready for machine learning algorithms.

In the project that used this dataset, the samples were slightly imbalanced after preprocessing. To address this issue, the Synthetic Minority Over-sampling Technique (SMOTE) was applied to the data to balance the classes. This increased the number of samples in the dataset by 36.6%. The project involved visualizing the distribution of the data and the relationships between the features, which provided insights into the relationship between the feature set. Feature selection and elimination were also carried out to identify the most appropriate features to use in the machine learning models.

Multiple algorithms were tested, and the performance of each algorithm was fine-tuned using hyperparameters. The Logistic Regression, Decision Tree Classifier, Support Vector Machine Classifier, K-Nearest Neighbours Classfier, Gradient Boosting Classifier, Extreme Gradient Boosting Classfier Random Forest Classifier, and Naive Bayes algorithms were tested. Overall, this dataset is a useful resource for exploring the relationship between BMI and other factors such as age, gender, height, and weight. It can also be used to build machine learning models for predicting an individual's BMI.

# Results

A number of significant results from the study have improved our comprehension of the data and how different machine learning algorithms perform with this specific dataset. Below is a summary of some of the project's major results:

• Firstly, the dataset was relatively small, containing approximately 500 samples. However, after preprocessing, which involved dropping 0.6% of the data samples, the dataset was deemed suitable for further analysis.

• Secondly, we discovered that the samples were somewhat imbalanced after preprocessing. To address this issue, we applied the SMOTE technique to balance the classes, which added 36.6% more samples to the dataset.

• Thirdly, visualizing the distribution of the data and the relationships between the features provided us with valuable insights into the feature-set and helped us to better understand the data.

• Fourthly, feature selection and elimination were performed, and the most relevant features were shortlisted, leading to improved model performance.
• Fifthly, we tested multiple algorithms, fine-tuning hyperparameters, and this allowed us to gain a deeper understanding of how the different algorithms performed on this specific dataset.

• Sixthly, we found that the LR, Random Forest Classifier, and XG-Boosting algorithms performed exceptionally well on the current dataset, especially when considering the recall score as the key metric.

Overall, the project demonstrated the importance of carefully preprocessing data and performing feature selection to obtain optimal results. The use of the SMOTE technique also proved to be a useful tool for balancing imbalanced datasets.
