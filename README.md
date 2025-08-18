# 🩺 Diabetes Prediction Project

**Diabetes Prediction Project** is a **Data Science project** that predicts whether a female patient is likely to have diabetes (`Outcome = 1`) or not (`Outcome = 0`). The prediction is based on key health attributes collected from the patient.

The dataset includes features such as **Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, and Age**, which are used to train and evaluate predictive models.

---

## 🎯 Project Objective
- A **self-learning project** to explore and implement various machine learning algorithms.
- Build a **predictive model** that can help identify individuals at risk of diabetes using medical data.

---

## 📂 Dataset
- **Source:** [Diabetes Dataset - Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset/data)
- **Description:** The dataset contains multiple medical predictor variables and one target variable (`Outcome`). Each feature represents a health factor influencing diabetes risk:

| Feature | Description |
|---------|-------------|
| **Pregnancies** | Number of pregnancies. Higher counts may increase the risk of gestational diabetes. |
| **Glucose** | Plasma glucose concentration. High levels are a major risk factor. |
| **Blood Pressure** | Diastolic blood pressure (mm Hg). High BP is linked to insulin resistance. |
| **Skin Thickness** | Triceps skinfold thickness (mm). Indicates body fat level. |
| **Insulin** | Two-hour serum insulin (mu U/ml). Abnormal levels may indicate insulin resistance. |
| **BMI** | Body Mass Index (kg/m²). Higher BMI increases type 2 diabetes risk. |
| **Diabetes Pedigree Function** | Probability of diabetes based on family history and genetics. |
| **Age** | Risk increases with age, especially after 45. |

---

## 🛠️ Tools & Technologies
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, etc.  
- **Tools:** Jupyter Notebook, VS Code  
- **Algorithms Implemented:** Random Forest Classifier, Support Vector Machine (SVM), k-Nearest Neighbors (KNN), Logistic Regression, Gradient Boosting Classifier, Multilayer Perceptron (MLP)  

---

## 📊 Key Results

### Data Analysis
1. **Diabetes vs Non-Diabetes Distribution**  
<img width="484" height="488" alt="image" src="https://github.com/user-attachments/assets/94a8f7c5-0d9e-4fd3-b5ff-9513c216c717" />


2. **Correlation Heatmap**  
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405540102221992006/image.png?ex=689f32ba&is=689de13a&hm=07875bdc4c73df4227f5de557dfe99d08a57e9603769934af432955d8f66cea4&">


3. **Boxplots of Outcome vs Key Features**  
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405540911554891806/image.png?ex=689f337b&is=689de1fb&hm=e8bd5a1e4b123df7c7eed0344cb0db87168dda1c8f4aae410682703e55979e1f&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405540959466426369/image.png?ex=689f3386&is=689de206&hm=cd20d9d83c5c53dae09e1fb64cb83f0e63f34ae92a7c2bb1ec2286bbeb40b9e7&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405541017771573268/image.png?ex=689f3394&is=689de214&hm=b37640ff983a1bb063d65c39a240424792ad97cf102e5f1355e68645702c8b74&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405541066014457976/image.png?ex=689f339f&is=689de21f&hm=9e14f5e6ab2d01357dddb6a678ce5627b24a41c1c2d28e931aa7259c0cbb4f8e&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405541106430509147/image.png?ex=689f33a9&is=689de229&hm=02414530ae93fc78707523dc888db7fb77b4e463fedb6a5a740d74b22baf1cfe&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405541177801048094/image.png?ex=689f33ba&is=689de23a&hm=30589ba57fadbc8fb787ed07419ca2a988e14f30dd43d05ab979c60f393442f3&">


### Model Performance
1. **Accuracy of All Models**  
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405543118841053274/image.png?ex=689f3589&is=689de409&hm=2125fdaa509fa05f8d09551bfa60355207008c112775e949f16f9c14aa528e8e&">


2. **Confusion Matrices**  
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405543577152393287/image.png?ex=689f35f6&is=689de476&hm=0b95f79185bb31686544c8b0d81873385180ed2dc74a41a071f75197a914ae35&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405543619213000754/image.png?ex=689f3600&is=689de480&hm=0e3986c6f4304aef46c15406b15b70793e0bda541f6bdb0b0e8eb83d72e0d0ef&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405543683528589493/image.png?ex=689f360f&is=689de48f&hm=702bee7be9f14f3e2afe59d9d905dbbb8246c3cb2ca54f0dc31119ba8950962e&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405543733088223303/image.png?ex=689f361b&is=689de49b&hm=c29300b0d384c06e5d1ed91af7e0a13916da4665c16d77c199e891a845177bd2&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405543783675723946/image.png?ex=689f3627&is=689de4a7&hm=d35a08abda28052f531138090490d5110f5bdbf9573d34c7f1247b3e2bd09aac&">
<img src="https://cdn.discordapp.com/attachments/459760410875396139/1405543837405024257/image.png?ex=689f3634&is=689de4b4&hm=7b12dcee07c0a344c68d82da6862e1139520359e56b263b18fd7e1bf56fd84cf&">

---

## 📅 Future Improvements
1. Enhance model performance.  
2. Include additional features and external data sources.  
3. Collect more samples to improve training accuracy and generalization.

---
