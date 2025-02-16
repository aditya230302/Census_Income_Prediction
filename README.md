# Census_Income_Prediction

In this project, initially we need to preprocess the data and then develop an understanding of the different features of the data by performing exploratory analysis and creating visualizations. Further, after having sufficient knowledge about the attributes, we will perform a predictive task of classification to predict whether an individual makes over 50,000 a year or less by using different machine learning algorithms.

### **Data Information**

- last column is income so I will rename it to Annual Income
- age: the age of an individual.
- workclass: The type of work or employment of an individual. It can have the following categories:
    - Private: Working in the private sector.
    - Self-emp-not-inc: Self-employed individuals who are not incorporated.
    - Self-emp-inc: Self-employed individuals who are incorporated.
    - Federal-gov: Working for the federal government.
    - Local-gov: Working for the local government.
    - State-gov: Working for the state government.
    - Without-pay: Not working and without pay.
    - Never-worked: Never worked before.
- Final Weight: The weights on the CPS files are controlled to independent estimates of the civilian noninstitutional population of the US. These are prepared monthly for us by Population Division here at the Census Bureau. We use 3 sets of controls.
- education: The highest level of education completed.
- education-num: The number of years of education completed.
- marital-status: The marital status.
    -  Married-civ-spouse corresponds to a civilian spouse
    -  Married-AF-spouse is a spouse in the Armed Forces
- occupation: Type of work performed by an individual.
- relationship: The relationship status.
- race: The race of an individual.
- sex: The gender of an individual.
- capital-gain: The amount of capital gain (financial profit).
- capital-loss: The amount of capital loss an individual has incurred.
- hours-per-week: The number of hours works per week.
- native-country: The country of origin or the native country.
- income: The income level of an individual and serves as the target variable. It indicates whether the income is greater than $50,000 or less than or equal to $50,000, denoted as (>50K, <=50K).


![{A58DF96F-3241-4D8B-9BB4-2CD42DF0E69B}](https://github.com/user-attachments/assets/abb3ca7a-c5c9-41a4-b606-96f668e5a7fa)

![{DB0C60EE-4566-4185-ACA6-C6CB4100F22F}](https://github.com/user-attachments/assets/38373852-20ca-4b37-a772-625dc4e9bf5e)

![image](https://github.com/user-attachments/assets/c86fd350-1a39-4665-b23e-678b8240f0d3)

![{05220151-A6EA-4F61-B1FB-C33211053825}](https://github.com/user-attachments/assets/41d22b27-0af2-475b-b88b-74e61ff8bdf0)

![{2674B91B-8BFA-4200-B9CC-A85C8BA58F04}](https://github.com/user-attachments/assets/21e824b5-92c1-41b6-ac0f-0aa739bfa742)

![{1DC3E0D9-EBEA-4B30-BA7F-349B37F5D715}](https://github.com/user-attachments/assets/82de181c-26ae-4729-bf43-1bbb32f16ecf)

### **for this model - Random Forest > SVM > Logistic Regression > Decision Tree**
