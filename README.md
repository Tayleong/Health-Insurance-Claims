# Health-Insurance-Cost-Prediction Using Python
This capstone project applies machine learning techniques to predict annual medical insurance claim costs. Using a synthetic dataset, we explore linear regression, random forest, and gradient boosting models to identify key cost drivers such as smoking status, BMI, and blood pressure.

https://imgur.com/a/ReINHuY

### <font color='darkblue'> **1. 📁 Dataset Description:**</font>

The dataset used in this project contains synthetic health insurance claim data for individual patients. Each record represents a single insured person along with various demographic, health, and lifestyle variables, and their corresponding annual medical claim amount.

### <font color='darkblue'> **2. Key Features:**</font>

**Column Name	Description**

1) **Age**:	Age of the individual (in years)

2) **Gender**:	Gender of the individual (male, female)

3) **BMI (Body Mass Index)**: A measure of body fat

4) **Bloodpressure**	Systolic blood pressure reading

5) **Children**:	Number of Patients children

6) **Smoker**:	Whether the person is a smoker (Yes, No)

7) **Region**:	Geographic region (northeast, southeast, etc.)

8) **Diabetic**:	Indicates if the person is diabetic (Yes, No)


### <font color='darkblue'> **3. 🔍 General Observations**</font>

1) **Gender**: Distribution is nearly equal between male and female patients.

2) **Smoker**: Roughly 20–25% of patients are smokers.

3) **Region**: Southeast has the most patients.

4) **Diabetic**: With 642 patients marked as diabetic (~48%), this indicates that almost half of the population in the dataset is living with diabetes. This suggest that diabetes is a major health factor in this dataset and highly potential to affect the claim impact.

5) **Patient Dependant_Children**: Majority of patients have 0 to 2 children and few patients report have 4 or more children.

6) **Age**: Histogram generally shows uniform distribution. Boxplot shows no outliers.

7)  **BMI (Body Mass Index)**: Distribution is slightly right-skewed with a concentration between 25 and 35. Boxplot shows some outliers above BMI 45.

8)  **Bloodpressure**: Appears normally distributed, centered around 90–95. Boxplot reveals multiple outliers on the higher end (possibly hypertension).

9)  **Claim (Insurance Claim Amount)**: Highly right-skewed distribution. Majority of claims are low, but long tail of high values. Boxplot shows many extreme outliers.


### <font color='darkblue'> **3. 💡 Key Insights**</font>

1) Smoking is the strongest predictor of higher claims across all models.

2) BMI and blood pressure are strong continuous cost drivers. Every unit increase in BMI correlates with thousands of dollars in added annual claim burden.

3) Gradient Boosting outperformed all other models (R² = 0.8484), suggesting that non-linear interactions between features are important to accurately predicting claims.


### <font color='darkblue'> **4. Other Comments**</font>

1) This dataset is good for prototyping risk-based pricing models for health insurance.

2) Future enhancements could include:

3) Time--series claim history

4) Medication use

5) Hospital visits or diagnoses

6) Ethical consideration: Predictive models in healthcare must be validated against bias and fairness, especially when used in pricing or coverage decisions

7) Pricing strategies should account for country-specific healthcare policies and subsidies (If any), as these were not explicitly detailed in the dataset.
