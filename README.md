# Health-Insurance-Cost-Prediction
This capstone project applies machine learning techniques to predict annual medical insurance claim costs. Using a synthetic dataset, we explore linear regression, random forest, and gradient boosting models to identify key cost drivers such as smoking status, BMI, and blood pressure.

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

1) Gender: Distribution is nearly equal between male and female patients.

2) Smoker: Roughly 20–25% of patients are smokers.

3) Region: Southeast has the most patients.

4) Diabetic: With 642 patients marked as diabetic (~48%), this indicates that almost half of the population in the dataset is living with diabetes. This suggest that diabetes is a major health factor in this dataset and highly potential to affect the claim impact.

5) Patient Dependant_Children: Majority of patients have 0 to 2 children and few patients report have 4 or more children.

6) Age: Histogram generally shows uniform distribution and Boxplot shows no outliers.


