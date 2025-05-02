Stroke Prediction Analysis
A machine learning project that predicts the likelihood of stroke occurrence based on clinical and demographic data. This end-to-end pipeline includes data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and result visualization.



📂 Project Structure

📦stroke-prediction-analysis
 ┣ 📈 Stroke_prediction_analysis.ipynb
 ┣ 🖼️ Age.png
 ┣ 🖼️ BMI.png
 ┣ 🖼️ Average glucose level.png
 ┣ 🖼️ correlation heatmap.png
 ┣ 🖼️ Cross validation accuracy comparison.png
 ┣ 🖼️ gender distribution.png
 ┣ 🖼️ stroke distribution visualization.png
 ┣ 🖼️ stroke probablity by smoking status and gender.png
 ┗ 📄 README.md



 
📌 Overview
This project leverages machine learning to assess stroke risk based on patient features like:

Age, gender, and marital status

Health indicators (e.g., hypertension, heart disease, glucose level, BMI)

Lifestyle features (e.g., work type, smoking status)





🔬 Dataset
Source: Stroke Prediction Dataset (Kaggle)

Target Variable: stroke (1 = stroke occurred, 0 = no stroke)

Missing Values: Handled in bmi via mean imputation

Categorical Features: Encoded using LabelEncoder and one-hot encoding





📊 Visualizations
Stroke Distribution

Gender Distribution

Age Distribution


BMI Distribution


Average Glucose Level Distribution

Correlation Heatmap

Stroke by Smoking Status and Gender

Cross-Validation Accuracy Comparison

🤖 Models Trained
Decision Tree Classifier

Random Forest Classifier

K-Nearest Neighbors

Voting Classifier (Ensemble)

🛠 Techniques Used
Label Encoding

One-Hot Encoding

IQR-based outlier detection

GridSearchCV for hyperparameter tuning

Stratified Train-Test Split




📈 Results
All models were tuned using 5-fold cross-validation. The ensemble VotingClassifier provided balanced and reliable results.

▶️ How to Run
Clone the repo:

git clone https://github.com/Haboye05/stroke-prediction-analysis.git
cd stroke-prediction-analysis
Open the notebook:


jupyter notebook Stroke_prediction_analysis.ipynb
Run the notebook cells sequentially.

📌 Author
Habeeb Oyediran
Connect with me on GitHub
