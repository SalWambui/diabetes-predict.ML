# Machine Learning Project: Diabetes prediction

# 📌Project overview
This project uses Machine Learning to predict whether a person is likely to have diabetes based on medical diagnostic data. The model is built using Python and trained on a supervised learning algorithm.

It demonstrates the full ML workflow:

- Data loading and preprocessing
- Feature scaling
- Model training
- Prediction on new data

# 📊 Dataset

The dataset used is the Pima Indians Diabetes Dataset, which includes medical attributes such as:

- Glucose level
- Blood pressure
- BMI
- Age
- Insulin levels
- Number of pregnancies

# ⚙️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook


# 🤖 Machine Learning Workflow
1. Load dataset using Pandas
2. Split data into training and testing sets
3. Standardize features using StandardScaler
4. Train classification model
5. Evaluate model performance
6. Make predictions on new input data

# 🧪 How to Run the Project
## 1. Clone the repository
git clone https://github.com/your-username/diabetes-prediction.git
## 2. Navigate into the project folder
cd diabetes-prediction
## 3. Install required libraries
pip install -r requirements.txt
## 4. Run the Jupyter Notebook
jupyter notebook

# 📥 Making Predictions

The model takes input in the following format:

(Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age)

Example:

input_data = (4, 110, 92, 0, 0, 37.6, 0.191, 30)

# 📈 Model Performance

The model is evaluated using accuracy score on test data.
It performs reasonably well for binary classification tasks.

# 📁 Project Structure
diabetes-prediction/
│
├── diabetes_prediction.ipynb   # Main notebook
├── dataset.csv                 # Dataset file
├── scaler.pkl                  # Saved scaler (optional)
├── model.pkl                   # Trained model (optional)
├── requirements.txt            # Dependencies
└── README.md                   # Project documentation

# 🚀 Future Improvements
- Improve accuracy using advanced models (Random Forest, XGBoost)
- Add hyperparameter tuning
- Deploy model using Flask or Streamlit
- Build a web-based prediction app
