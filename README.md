# Student Placement Prediction (Logistic Regression)

This project predicts whether a student will get **placed** or **not placed** based on their **CGPA** and **IQ** scores.
It is a simple Machine Learning classification project using **Logistic Regression**, built and trained in **Google Colab**.

---

## Project Overview

* Dataset: **100 students**
* Features used:

  * **CGPA**
  * **IQ**
* Target variable:

  * **Placement (0 = Not Placed, 1 = Placed)**

The goal is to train a Logistic Regression model that can classify whether a student will be placed based on the given features.

---

## Machine Learning Pipeline

1. **Load Dataset**
   Read the CSV file containing student data.

2. **Data Cleaning**
   Removed the first unnecessary column.

3. **Train-Test Split**
   Data was split into training (90%) and testing (10%).

4. **Feature Scaling**
   Standardized features using `StandardScaler` to bring all values on the same scale.

5. **Model Building**
   Trained a **Logistic Regression** classifier.

6. **Evaluation**
   Calculated accuracy using `accuracy_score`.

7. **Visualization**
   Plotted the decision boundary using `plot_decision_regions`.

8. **Model Saving**
   Exported the trained model as **model.pkl** using the `pickle` library.

---

## 🗂️ Files Included

* `placement.csv` — Dataset
* `model.pkl` — Saved ML model
* `.ipynb` / `.py` file — Model training notebook/script
* `README.md` — Project documentation

---

## 📊 Libraries Used

* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Pickle
* Mlxtend (for decision boundary plotting)

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```
   git clone <https://github.com/Lokesh-padhanaya/End-to-end-machine-learning-project.git>
   ```
2. Open the notebook in **Google Colab** or local Jupyter.
3. Install required libraries:

   ```
   pip install numpy pandas scikit-learn matplotlib mlxtend
   ```
4. Run all the cells to train the model.
5. The trained model will be saved as `model.pkl`.

---

## 🧾 Model Accuracy

Accuracy may vary slightly due to random train-test split.
Typical accuracy: **~85–95%** depending on the split.

---

## Future Improvements

* Add more features (e.g., communication skills, projects count, internship experience)
* Try more ML models (SVM, KNN, Random Forest)
* Deploy the model using Flask or Streamlit

---

## Author

Created for learning Machine Learning basics and model deployment.
