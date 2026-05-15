# 🏃 Walk vs Run Classification Project

## 📌 Project Overview
This project focuses on building a Machine Learning classification model that predicts whether a person is **Walking** or **Running** using motion sensor data.

The dataset contains sensor readings such as acceleration and gyroscope values collected from wearable/mobile sensors.

The main goal of this project is to analyze motion patterns and accurately classify human physical activity.

---

# 🎯 Objective
- Build a binary classification model to predict:
  - **Walk**
  - **Run**
- Perform data preprocessing and feature engineering.
- Apply Exploratory Data Analysis (EDA).
- Train and evaluate multiple Machine Learning models.
- Compare model performance and select the best model.

---

# 📂 Dataset Information
The dataset contains sensor-based features such as:

| Feature | Description |
|---|---|
| acceleration_x | Acceleration along X-axis |
| acceleration_y | Acceleration along Y-axis |
| acceleration_z | Acceleration along Z-axis |
| gyro_x | Gyroscope movement on X-axis |
| gyro_y | Gyroscope movement on Y-axis |
| gyro_z | Gyroscope movement on Z-axis |
| activity | Target variable (Walk / Run) |

---

# 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

# 📊 Project Workflow

## 1. Data Understanding
- Dataset inspection
- Domain analysis
- Understanding sensor features

## 2. Data Preprocessing
- Handling null values
- Removing duplicates
- Dropping unnecessary columns
- Encoding categorical variables
- Feature scaling

## 3. Exploratory Data Analysis (EDA)
- Univariate analysis
- Correlation analysis
- Distribution plots
- Sensor behavior comparison

## 4. Model Building
Multiple classification algorithms were implemented:

1. Logistic Regression
2. Random Forest Classifier
3. XGBoost Classifier
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors (KNN)
6. Decision Tree Classifier

## 5. Model Evaluation
Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

# 🚀 Installation & Setup

## Clone the Repository
```bash
git clone https://github.com/urvilranpariya/WalkRunPrediction-Rubixe.git
```

## Navigate to Project Folder
```bash
cd walk-run-classification
```

## Install Dependencies
```bash
pip install -r requirements.txt
```

## Run Jupyter Notebook
```bash
jupyter notebook
```

---

# ▶️ Usage
1. Open the notebook file.
2. Run all cells sequentially.
3. Train and evaluate models.
4. Compare model performances.

---

# 📈 Key Learning Outcomes
- Data preprocessing techniques
- Sensor data analysis
- Feature scaling
- Classification algorithms
- Model evaluation and comparison
- Human Activity Recognition (HAR)

---

# 📁 Project Structure
```bash
walk-run-classification/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── WalkRunClassification.ipynb
│
├── README.md
├── requirements.txt
└── models/
```

---

# 📌 Future Improvements
- Deploy model using Flask/FastAPI
- Real-time activity prediction
- Deep Learning implementation
- Mobile application integration


---

# 📜 License
This project is for educational and learning purposes.

---

