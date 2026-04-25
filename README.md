<h1 align="center">🫁 Lung Cancer Prediction using Machine Learning</h1>

![Lung cancer image](https://github.com/user-attachments/assets/e3312178-0b70-476e-a832-8c702965c2b0)

## **📌 Project Overview**
Lung cancer is one of the leading causes of death worldwide. Early detection and prediction can play a vital role in timely diagnosis and treatment. This project aims to build a machine learning model that predicts the likelihood of lung cancer in a person based on various health and lifestyle factors such as smoking, age, and chronic diseases.

## **🎯 Objectives**
* Analyze patient survey data to identify key features affecting lung cancer.
* Build and train multiple machine learning models.
* Compare model performance using standard metrics.
* Enhance prediction reliability using **Ensemble Learning (Voting Classifier)**.

## **📊 Dataset Description**
The dataset consists of **309 entries** and **16 columns**. After data cleaning (removing 33 duplicates), the final dataset contained **276 entries**.

**Features:**
* **Demographics:** Gender, Age.
* **Health & Symptoms:** Yellow fingers, Anxiety, Chronic disease, Fatigue, Allergy, Wheezing, Coughing, Shortness of breath, Swallowing difficulty, Chest pain.
* **Lifestyle:** Smoking, Peer pressure, Alcohol consumption.
* **Target Variable:** `LUNG_CANCER` (Yes/No).

## **🛠️ Tech Stack & MethodsLanguages:** 
* **Python Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Plotly, Scikit-learn
* **Preprocessing:**
     * Label Encoding (converting categorical to numerical).
     * Feature Scaling (StandardScaler) to ensure all features are on the same scale.
* **Feature Selection:** Sequential Feature Selector was used to identify the most impactful features for the model.

## **🤖 Models Implemented** 
We evaluated several classification algorithms:
**1. Logistic Regression (Baseline Model)**
**2. Decision Tree Classifier**
**3. Support Vector Machine (SVM)**
**4. Gaussian Naive Bayes**
**5. K-Nearest Neighbors (KNN)**
**6. Voting Classifier (Ensemble):** Combined all the above models using a "soft" voting approach.

## **📈 Results & Performance**
The models were evaluated based on Training and Testing accuracy:
| Model | Training Score | Testing Score |
|----------|----------|----------|
| **Logistic Regression** | 92.72% | **92.85%** |
| **KNN** | 93.18% | **89.28%** |
| **SVM** | 94.54% | **85.71%** |
| **Naive Bayes** | 90.90% | **91.07%** |
| **Decision Tree** | 96.36% | **94.64%** |
| **Voting Classifier** | 95.90% | **94.64%** |

**Note:** Logistic Regression achieved the same score of both testing set and testing set of **92%** in this specific experiment.

## **🚀 How to Run**
1. Clone the repository.
2. Install requirements: `pip install pandas numpy seaborn matplotlib scikit-learn mlxtend`.
3. Run the Jupyter Notebook or Python script to train the model and see visualizations.

## **🤝 Connect with Me**
If you have any questions or would like to collaborate, feel free to reach out!
* **LinkedIn:** [Mudhassir](https://www.linkedin.com/in/mudhassir-s/)
* **Email:** mudhassirofficial@gmail.com
* **GitHub:** [Mudhassir](https://github.com/Mudhaasir-S)
