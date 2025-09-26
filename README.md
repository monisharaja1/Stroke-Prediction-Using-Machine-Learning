 🧠 Stroke Prediction Using Machine Learning  
This repository contains an **end-to-end Machine Learning project** that predicts the risk of stroke based on patient health records.  
The project covers everything from **data preprocessing, exploratory data analysis (EDA), model training & evaluation, to deployment with a Gradio web app**. 
📌 Project Overview  
Stroke is one of the major causes of death and disability worldwide.  
Early stroke prediction can play a vital role in **preventive healthcare**.  
In this project, we:  
- Preprocessed and analyzed healthcare data.  
- Built **Logistic Regression** and **Random Forest** models.  
- Evaluated performance using accuracy, confusion matrix, ROC curve, and feature importance.  
- Developed an **interactive Gradio web application** for real-time predictions.  
 📂 Dataset  
The dataset used is the **Healthcare Dataset Stroke Data**, which includes features like:  

- `gender`  
- `age`  
- `hypertension`  
- `heart_disease`  
- `ever_married`  
- `work_type`  
- `Residence_type`  
- `avg_glucose_level`  
- `bmi`  
- `smoking_status`  
🎯 **Target Variable**:  
- `stroke` → (1 = Stroke, 0 = No Stroke)  
 🚀 Workflow
**Data Preprocessing**  
   - Handled missing values (BMI).  
   - Encoded categorical features using `LabelEncoder`.  
   - Standardized numerical features.  
**Exploratory Data Analysis (EDA)**  
   - Stroke distribution (imbalanced dataset).  
   - Age vs Stroke, Glucose Levels vs Stroke, BMI impact.  
**Model Building**  
   - Logistic Regression  
   - Random Forest Classifier  
 **Model Evaluation**  
   - Accuracy & Classification Report  
   - Confusion Matrix  
   - ROC Curve & AUC Score  
   - Feature Importance  
 **Deployment with Gradio**  
   - User-friendly web app interface.  
   - Sliders & dropdowns for patient inputs.  
   - Prediction results with stroke probability visualization.  
   - Additional insights: Confusion Matrix, ROC Curve, Feature Importance plots.  
 🛠️ Tech Stack  
- **Python**  
- **Pandas, NumPy** → Data preprocessing  
- **Matplotlib, Seaborn** → EDA & Visualization  
- **Scikit-learn** → Machine Learning models & evaluation  
- **Gradio** → Interactive Web App Deployment  
 ⚡ How to Run  

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/stroke-prediction.git
   cd stroke-prediction

   👩‍💻 Author

Monisha Raja.P
MSc Data Science Student
