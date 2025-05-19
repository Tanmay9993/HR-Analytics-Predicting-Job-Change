# 📊 HR Analytics: Predicting Job Change of Data Scientists

## 🔍 Overview
This project predicts whether data science trainees are likely to switch jobs after training. By identifying such intent, companies can optimize hiring efforts, personalize training, and reduce churn-related costs.

## 🎯 Purpose & Problem Statement
A data science company wants to identify which candidates from its training program are likely to look for external opportunities. This helps tailor training and recruitment pipelines toward committed candidates—saving time, improving training ROI, and ensuring alignment between training investments and hiring outcomes.

## 🛠️ Key Features & Workflow
- **Dataset Size**: 1,000 sample records from a real-world HR dataset
- **Tools Used**: Python, Pandas, Seaborn, Scikit-learn, RandomForest, GradientBoosting, Voting Classifier
- **Tasks Covered**:
  - Performed EDA on candidate demographics, education, and experience
  - Handled missing values, encoded categorical features, and dropped low-informative attributes
  - Identified key features like `training_hours` and `city_development_index` using Random Forest importance
  - Trained multiple models (SVM, Logistic, Random Forest, Gradient Boosting)
  - Tuned hyperparameters and ensembled classifiers using VotingClassifier for robust predictions

## 📈 Results & Visuals

### 🔹 City Development vs Job Change
Candidates from highly developed cities are less likely to switch jobs.  
<img width="712" alt="Screenshot 2025-05-19 at 4 23 35 PM" src="https://github.com/user-attachments/assets/86b3e708-4d99-42f7-a410-c3f49bb18817" />


### 🔹 Training Hours vs Job Change
Those with more training hours showed greater intent to switch jobs.  
<img width="741" alt="Screenshot 2025-05-19 at 4 23 49 PM" src="https://github.com/user-attachments/assets/a2e388ef-b4f7-4e43-9337-a1a15352693c" />


### 🔹 Relevant Experience vs Job Change
Candidates with prior experience are more likely to explore other jobs.  
<img width="494" alt="Screenshot 2025-05-19 at 4 24 10 PM" src="https://github.com/user-attachments/assets/6689ce6d-a7b9-4290-a2ff-15ff196a333e" />


### 🔹 Education vs Experience Correlation
Visualizing overlap of education level with relevant experience.  
<img width="504" alt="Screenshot 2025-05-19 at 4 24 24 PM" src="https://github.com/user-attachments/assets/aa6bac6f-4829-4a29-88bd-5ce131fc92be" />


### 🔹 ROC Curve (Final Model)
Visualizing classifier performance on the test set.  
<img width="410" alt="Screenshot 2025-05-19 at 4 24 44 PM" src="https://github.com/user-attachments/assets/2f988eb9-c157-4d03-9761-d83532b65db1" />



## ✅ Final Accuracy
- **Best Model**: Gradient Boosting Classifier with tuned hyperparameters  
- **Accuracy**: ~78.4% on test set  
- **Improvement**: +3.6% boost after tuning compared to baseline

## 📊 Data Source
Dataset from [Kaggle – HR Analytics: Job Change of Data Scientists](https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists)

---

