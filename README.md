# classify_diabetics.py
# Diabetes Prediction using Logistic Regression
This project demonstrates a simple implementation of a binary classification model using **Logistic Regression** on a manually created dataset that mimics the **Pima Indians Diabetes dataset**. The goal is to predict whether a patient has diabetes based on medical attributes.
## 📁 Dataset
The dataset is manually created within the script and contains the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: A function that scores likelihood of diabetes based on family history
- **Age**: Age of the patient (years)
- **Outcome**: Class variable (0 = Non-diabetic, 1 = Diabetic)
## 🧠 Model
- **Algorithm**: Logistic Regression
- **Library Used**: `scikit-learn`
- **Train-Test Split**: 75% training, 25% testing
- **Performance Metrics**:
  - Confusion Matrix
  - Accuracy Score
## 📊 Visualization
- Pair plot of features using **Seaborn**
- Heatmap of the confusion matrix
## 🛠 Requirements
Install the required Python libraries using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
````
## 🚀 How to Run
1. Clone the repository.
2. Run the Python script:
   ```bash
   python diabetes_prediction.py
   ```
   The script will:
* Display the first few rows of the dataset
* Visualize feature distributions
* Train a logistic regression model
* Display the confusion matrix and accuracy
* Plot the confusion matrix using seaborn
## 📌 Note
This is a **demonstration project** with a small manually defined dataset for simplicity and understanding. For production or real-world usage, use larger, validated datasets like the original Pima Indians Diabetes dataset from Kaggle or UCI ML Repository.
