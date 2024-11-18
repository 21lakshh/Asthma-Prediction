# **Asthma Prediction**  
A machine learning model designed to predict the likelihood of asthma occurrence or exacerbation based on multiple data inputs, including demographic, environmental, clinical, and lifestyle factors.

## **Overview**  
Asthma is a chronic respiratory condition that affects millions worldwide. Early prediction of asthma risks can enable timely intervention, improve quality of life, and reduce healthcare costs. This model leverages machine learning to provide accurate predictions, aiding both individuals and healthcare providers in proactive asthma management.

### **Features**  
The dataset includes property attributes such as:  

- PatientID 
- Age 
- Gender 
- Ethnicity 
- EducationLevel 
- BMI 
- Smoking 
- PhysicalActivity
- DietQuality
- SleepQuality
- PollutionExposure
- PollenExposure
- DustExposure
- PetAllergy
- FamilyHistoryAsthma
- HistoryOfAllergies
- Eczema
- HayFever
- GastroesophagealReflux
- LungFunctionFEV1
- LungFunctionFVC
- Wheezing
- ShortnessOfBreath
- ChestTightness
- Coughing
- NighttimeSymptoms
- ExerciseInduced
- Diagnosis
- DoctorInCharge



#### **Approach**
**Data analysis** : Using heatmap to check correaltion between multiple features, Using pie charts to check gender,smoke and people diagnosed with asthma distribution, count plot to display number of males and femlaes having asthma compared to ones not having asthma and checking the age distribution  
**Data Preprocessing** : Removed unnecessary features like DoctorInCharge,PatientID and EducationLeve, had no missing values and no categorical data that needed to be encoded into numeric values  
**Model Selection**: Tested Logistic regression model  
**Model Evaluation**  
- Accuracy on Training Data: 94.82%  
- Accuracy on Testing Data: 94.70%  

##### **Getting Started**
Clone the repo and install dependencies. 
