# Diabetes Prediction

The involves a dataset, PimaDiabetes.csv, derived from one originally collected by
the USA’s National Institute of Diabetes and Digestive and Kidney Diseases1. It lists various diagnostic
measures recorded from 750 women along with a 0/1 variable, Outcome, that indicates whether
the person eventually tested positive for diabetes. Table 1 shows the first few rows of the dataset
while the diagnostic measures are explained below.

Pregnancies: number of times the woman has been pregnant

Glucose: plasma glucose concentration (mg/dl) at 2 hours in an oral glucose tolerance test (OGTT)

Blood Pressure: Diastolic blood pressure (mm Hg)

Skin Thickness: Triceps skin fold thickness (mm)

Serum Insulin: insulin concentration2 (μ U/ml) at 2 hours in an OGTT

BMI: body mass index (weight in kg)/(height in m)2

Diabete Pedigree: a numerical score designed to measure the genetic influence of both the woman’s diabetic and her non‑diabetic relatives on diabetes risk: higher scores mean higher risk. Youcan read more about this in Smith, Everhart, Dickson, Knowler, and Johannes (1988).

Age: in years

Outcome: 1 if the woman eventually tested positive for diabetes, zero otherwise


## 1000 words report & code for the following tasks -

1. Write a brief description of the data, including its origin and quality issues. You should imagine
you are writing for a group who have no idea what this dataset is about. 

2. Do an exploratory data analysis. 

3. Add a column, ThreeOrMoreKids, to the dataset that answers the question “Does the woman
have 3 or more children?”, then fit an appropriate regression model to predict whether a
woman will develop diabetes using ThreeOrMoreKids as a single predictor. With the help of
the fitted model, answer the following questions (show your calculations, either by hand or
with help of R or Python): 
• What is the probability that you get diabetes, given that you have two or fewer children?
• What is the probability that you get diabetes, given that you have three or more children?

4. Using the data in PimaDiabetes.csv, fit appropriate regression models and use them to
determine how likely the women whose data are listed in Table 2 are to develop diabetes. You
are free to choose which explanatory variables to inclue in your model and may, if you like,
compare several models, but make sure that you clearly state the final model chosen and the
reasons behind this choice. With the help of your chosen model, interpret the results in terms
of probability of developing diabetes (as you did for the model based on ThreeOrMoreKids).

5. Include R or Python code used to produce the analysis.
