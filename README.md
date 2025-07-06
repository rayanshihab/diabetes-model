# 🩺 Diabetes Prediction Model

A supervised machine learning project to predict whether a patient is likely to have diabetes using the Pima Indians Diabetes Dataset.  
This notebook walks through data preprocessing, model training, evaluation, and visualization using core Python ML libraries.

---

## 🔍 Overview

This project aims to build a simple yet effective classifier for diabetes diagnosis. It can be used for educational, portfolio, or demo purposes to showcase understanding of the ML pipeline.

---

## 🧠 Model Pipeline

✅ Load and explore dataset using pandas  
✅ Handle missing values and normalize features  
✅ Split the dataset into train/test using train_test_split  
✅ Train a LogisticRegression model using scikit-learn  
✅ Evaluate using accuracy, precision, recall, and F1-score  
✅ Visualize performance using matplotlib

---

## 🛠 Technologies Used

- *Python 3*
- *pandas* – data manipulation
- *scikit-learn* – model training & evaluation
- *matplotlib* – visualization
- *Jupyter Notebook*

---

## 📊 Sample Results

| Metric     | Score |
|------------|--------|
| Accuracy   | 78%    |
| Precision  | 76%    |
| Recall     | 81%    |
| F1-score   | 78%    |

Visualizations include:
- Confusion Matrix
- Score bar chart per class

---

## ▶ How to Run

```bash
# Clone the repo
git clone https://github.com/rayanshihab/diabetes-model.git
cd diabetes-model

# (Optional) Create virtual environment
python -m venv env
source env/bin/activate  # or .\env\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook

Then open diabetes_model.ipynb and run all cells.
👨‍💻 Author

Rayan Shihab
🎓 Robotics & AI Engineering Student
🔗 GitHub: @rayanshihab
🧠 Passionate about AI, ML, and building intelligent systems

⸻

📌 Notes
	•	Dataset used: Pima Indians Diabetes Dataset
	•	This project is great for beginners to understand classification tasks in healthcare

⸻

🌟 Star This Repo!

If you find this useful, feel free to star ⭐ the repo and share!
