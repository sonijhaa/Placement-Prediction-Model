# Placement Prediction Model (XGBoost)

A machine learning model that predicts whether a student will be **Placed** or **Not Placed** based on academic performance, specialization, work experience, and aptitude test scores.  
The final model is built using **XGBoost** and also provides a **placement probability score**.

## Repository Structure
├── Placement_Prediction.ipynb # Complete ML pipeline
├── data/ # Dataset (optional)
├── images/ # Graphs & visualizations
├── requirements.txt # Dependencies
└── README.md # Documentation

## Dataset Features

| Column Name        | Description |
|--------------------|-------------|
| gender             | Male / Female |
| ssc_p              | Secondary Education % |
| ssc_b              | SSC Board |
| hsc_p              | Higher Secondary % |
| hsc_b              | HSC Board |
| hsc_s              | HSC Stream |
| degree_p           | Degree Percentage |
| degree_t           | Degree Type |
| workex             | Work Experience (Yes/No) |
| etest_p            | Employability Test Percentage |
| specialisation     | MBA Specialisation |
| mba_p              | MBA Percentage |
| status (target)    | Placed / Not Placed |

---

## Workflow

1. Load and clean dataset  
2. Encode categorical columns  
3. Train-test split (80/20)  
4. Scale numerical features  
5. Train **XGBoost Classifier**  
6. Evaluate model using:  
   - Accuracy  
   - Classification Report  
   - Confusion Matrix  
   - Feature Importance  
7. Visualizations (Seaborn & Matplotlib)  
8. Predict placement probability for new students

---

## Installation & Usage

Clone the repository:

git clone https://github.com/sonijhaa/placement-prediction-model.git
cd placement-prediction-model

# Install dependencies:
pip install -r requirements.txt

# Run the notebook:
jupyter notebook

# open
Placement_Prediction.ipynb








