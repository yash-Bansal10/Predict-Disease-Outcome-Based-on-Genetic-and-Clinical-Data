# Predict-Disease-Outcome-Based-on-Genetic-and-Clinical-Data

# 🧬 Disease Prediction Using Genetic, Clinical, and Lifestyle Data

This project uses supervised machine learning to classify patients as at-risk or not for a particular disease based on genetic markers, clinical symptoms, and lifestyle factors. The dataset contains diagnostic results and features derived from a combination of clinical and genomic data.

---

## 📁 Dataset

The dataset used contains:

- **ID** (Patient Identifier)
- **Diagnosis** (`M` = Malignant / at-risk, `B` = Benign / not at-risk)
- **Various Features** related to genetic markers, clinical tests, and lifestyle factors

The target column is `diagnosis`, which is encoded as:
- `1` = Malignant (at-risk)
- `0` = Benign (not at-risk)

---

## 💡 Objective

To develop a classification model that predicts whether a patient is at risk of a disease based on input features. The project compares different machine learning algorithms to determine the most accurate one.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab (for implementation)

---

## 📊 Models Used

- Random Forest Classifier
- Support Vector Machine (SVM)
- Logistic Regression

Each model is evaluated using:
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix

The best model is visualized using:
- Feature Importance (Random Forest)
- Confusion Matrix Heatmap

---

## 🔄 Workflow

1. Upload dataset via Google Colab file upload
2. Preprocess data (handle missing values, encoding, scaling)
3. Train and evaluate models
4. Visualize feature importance and confusion matrix
5. Identify best-performing model

---

## 📈 Sample Output

- Classification accuracy scores for all three models
- Top 20 important features (Random Forest)
- Heatmap of confusion matrix

---

## 📷 Screenshots

![image](https://github.com/user-attachments/assets/15b3c470-7658-4142-8a4d-66973a08920e)
![image](https://github.com/user-attachments/assets/9ac9bab1-87fc-4465-9247-2dbbb3df9093)



---

## 📚 References

- [Scikit-learn documentation](https://scikit-learn.org/)
- [Google Colab](https://colab.research.google.com/)
- Dataset provided as part of academic coursework.

---

## 👤 Author

**Yash Bansal**  
B.Tech CSE (AI)  
Krishna Institute of Engineering and Technology  
Roll No: 202401100300283

---

## 📬 Contributions

Pull requests are welcome! If you find any bugs or want to suggest improvements, feel free to open an issue.

