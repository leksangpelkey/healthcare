# healthcaredataset
Stroke prediction dataset

As per the WHO (World Health Organization) stroke is the 2nd leading cause of dead globally.

Dataset contents.

Columns Description:

id: unique identifier

gender: "Male", "Female" or "Other"

age: age of the patient

hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension

heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease

ever_married: "No" or "Yes"

work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"

Residence_type: "Rural" or "Urban"

avg_glucose_level: average glucose level in blood

bmi: body mass index

smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*

stroke: 1 if the patient had a stroke or 0 if not

Note: "Unknown" in smoking_status means that the information is unavailable for this patient

This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient. There are a total of 11 clinical features for predicting stroke events

Also, I am looking to find the answer for following question:

Who is likely to get stroke male, female?
Does age play a role in getting stroke?
Do children get stroke?
What is average glucose level for patients with stroke?
Does smoking has influence in getting stroke?
Does work_type predict stroke?
Does residence type predict stroke?
