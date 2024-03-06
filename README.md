# dsci-100-project_template
Template project repository for DSCI-100

**Introduction**
Heart disease is considered a significant cause of mortality around the world. Due to difficulties in providing accurate diagnoses, experts have turned to machine learning techniques in order to provide more accurate results to reduce the chances of misdiagnoses and fatality caused by cardiovascular diseases. 

We will be exploring [the heart disease Cleveland database](https://archive.ics.uci.edu/dataset/45/heart+disease). The cleveland database includes 302 rows and 14 variables: 
    - Age (Years)
    - Sex (1=male, 0=female)
    - CP: Chest pain type (Value 1: typical angina,  Value 2: atypical
           angin, - Value 3: non-anginal pa, -- Value 4: asymptoma)
    - trestbps: Resting blood pressure (mm HG)
    - chol: Serum cholestoral (mg/dl)
    - fbs: Fasting blood sugar>120mg/dl (1=true,0=false)
    - restecg: resting electrocardiographic results (0=normal, 1= has  
               ST-T wave abnormality)
    - thalach: max heart rate achieved
    - exang: Exercise induced agina (1=yes, 0=no)
    - oldpeak: ST deression induced by exercise relative to rest
    - slope: Slope of the peak exercise ST segment (1=upsloping,2=flat, 
             3=downsloping)
    - ca: Number of major vessels(0-3)
    - thal: 3=normal, 6=fixed defect, 7=reversable defect
    - num: Diagnosis of heart disease (0=absence, 1,2,3,4= present)

It is a multivariate dataset with categorical, integer and real variables. There are also variables with missing values (ca and thal)

We will be using the predictors age, chol, and trestbps (Resting blood pressure) to predict whether or not an individual will be diagnosed with heart disease. 

Question: How does a patient's age, cholesterol levels and resting blood pressure levels tell us about the liklelyhood of the patient being diagnosed with heart disease?

**Method**
We will be using the columns: Age_Of_Patient, Serum_Cholestrol(Mg/dl), Resting_Blood_Pressure to classify whether an individual will be predicted to have heart disease.  

**Expected outcomes and significance**
We expect to find a trend and relationship between a patient's age, cholesterol levels and resting blood pressure and whether they will get diagnosed with heart disease (i.e. patient with higher cholesterol, higher resting blood pressure and older age is predicted to have heart disease).

With these findings, we can make diagnosing heart disease more efficient and accurate, reducing the chances of misdiagnoses and reduce the fatality rates of heart disease.

With our findings, other researchers may be able to further research the causation between the relationships found in our analysis. Since we know correlation does not equal causation, others may be able to research what specificallt causes these trends. 


