# Job Experience Level Classifier

This project predicts the required **experience level** (e.g., Entry, Mid, Senior) for job postings based on key attributes such as median salary, remote eligibility, and sponsorship status. It applies classification techniques using K-Nearest Neighbors (KNN) and Decision Tree algorithms to uncover patterns in real-world job data.

---

## 📊 Project Objective

To build a machine learning model that can classify the experience level required for job postings using structured data, while demonstrating proficiency in data preprocessing, model evaluation, and performance tuning.

---

## 🛠 Technologies Used

- **Python** (pandas, NumPy, scikit-learn, matplotlib)
- **Jupyter Notebook / Google Colab**
- **KNN and Decision Tree Classification**
- **Data Preprocessing:** Label Encoding, MinMaxScaler
- **Evaluation:** Accuracy Score, Confusion Matrix, Classification Report
- **Visualization:** Accuracy vs K plot using Matplotlib

---

## 📁 Dataset

The dataset consists of job postings with features like:

- `med_salary`: Estimated median salary
- `remote_allowed`: Whether the job allows remote work
- `sponsored`: Whether the job post was sponsored
- `formatted_experience_level`: Target label (Entry, Mid, Senior, etc.)

---

## ✅ Project Workflow

1. **Data Cleaning**  
   Handled missing values and selected relevant features.

2. **Feature Engineering**  
   Applied Label Encoding and MinMax scaling for normalization.

3. **Model Building**  
   Built KNN and Decision Tree models to classify experience levels.

4. **Hyperparameter Tuning**  
   Plotted accuracy across different `k` values to identify optimal K for KNN.

5. **Evaluation**  
   Compared model performance using accuracy, confusion matrix, and classification report.

---

## 🔍 Results

- Achieved up to **85% accuracy** on test data.
- KNN performed well with `k=6` after tuning.
- Decision Tree provided interpretable structure with comparable accuracy.

---

## 🚀 How to Run

1. Clone the repository
2. Open the notebook (`.ipynb`) in Jupyter or Google Colab
3. Upload the dataset (`job_postings.csv`)
4. Run all cells

---

## 📌 Author

Sheetal Kumar – [LinkedIn](https://www.linkedin.com/in/sheetalkumar1418)

---

## 📎 License

This project is open-source and free to use under the MIT License.
