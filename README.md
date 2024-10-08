# Cadio-health-project
**Description:**
This is a supervised (classification) machine learning capstone project on Cardiovascular risk prediction, given by Alma Better.


![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

**Problem statement:**
Cardiovascular diseases (CVDs) are the leading cause of death globally, taking an estimated 18.6 million lives each year, which accounts for 33% of all the global deaths. CVDs are a group of disorders of the heart and blood vessels and include coronary heart disease, cerebrovascular disease, rheumatic heart disease and other conditions. More than four out of five CVD deaths are due to heart attacks and strokes, and one third of these deaths occur prematurely in people under 70 years of age.

It is important to detect cardiovascular disease as early as possible so that management with counselling and medicines can begin.

**Our main aim here is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).**

**Dataset description:**
The problem and aim stated above can be solved with the help of machine learning models and the data that we have. The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

**Variables:**
Each attribute is a potential risk factor. These attributes include demographic, behavioral, and medical risk factors.

**Defining the columns:**
**Demographic:**

• Sex: male or female("M" or "F")

• Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

**Behavioral:**

• is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

• Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

**Medical( history):**

• BP Meds: whether or not the patient was on blood pressure medication (Nominal)

• Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

• Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

• Diabetes: whether or not the patient had diabetes (Nominal)

**Medical(current):**

• Tot Chol: total cholesterol level (Continuous)

• Sys BP: systolic blood pressure (Continuous)

• Dia BP: diastolic blood pressure (Continuous)

• BMI: Body Mass Index (Continuous)

• Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)

• Glucose: glucose level (Continuous)

**Predict variable (desired target):**

• 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) - DV



![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

**Project Flowchart:**

Initial preparations(Loading the dependencies and the data)

**EDA**

**Clean-Up**


Handling null values.

Handling duplicate values.

Removing Outliers.

Feature engineering

Feature encoding

Grouping columns for better understanding.

Checking correlation for feature removal.

Checking the distribution of the data.

Pre processing of the data


Dealing with class imbalance.

Splitting and scaling the data.

Model implementation

1.Logistic regression.

2.Decision tree classifier.

3.Random forest classifier.

4.Gradient Boosting classifier.

5.Model explainability



![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

**Conclusion:**

**EDA Insights:**

1.People who have age between 47 to 65 have high chances of Positive CHD.

2.Being a Male has increase chances of Positive CHD.

3.People who are smoking has high chances of Positive CHD.

4.Persons taking BP Medicines has more chances of Positive CHD.

5.Prevalent Stroke and Prevalent Hypertension are also major factors which increases chances of CHD.

6.Person with Diabetes are more prone to Positive Coronary Heart Diseases.

**Results from ML Model:**


1.Logistic regression gives a ROCAUC score of 0.6277 on the testing set. This is worst performing model.

2.Decision tree model gives a ROCAUC score of 0.7069 on the testing set.

3.Random Forest Classifier model gives a ROCAUC score of 0.7533 on the testing set. This is the best performing model.

4.Gradient Boosting Classifier model gives a ROCAUC score of 0.7520 on the testing set.

5.Model explainability has been achieved by SHAP library's summary plot and an attribute called feature_importance_ of the tree based algorithms.

6.Total cholestrol and age are the two most important factors to predict the CHD risk factor.



![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)
