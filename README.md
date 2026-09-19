<div align="center">

# 🌸 Iris Classifier: Decoding Botanical DNA

### *Can we predict a flower's species just by looking at its petals? Let's find out.*

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0-orange?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

---

## 📖 The Mission (Overview)
This project was developed during my **CodeAlpha Data Science Internship**. While the Iris dataset is often considered the "Hello World" of Machine Learning, the goal here was to go beyond basic tutorials. I aimed to build a robust classification pipeline, deeply analyze feature correlations, and understand *why* certain models outperform others in botanical classification.

## 🧰 The Toolkit
*   **Data Wrangling:** `Pandas`, `NumPy`
*   **Visual Storytelling:** `Matplotlib`, `Seaborn`
*   **Machine Learning:** `Scikit-learn` (Logistic Regression, SVM, KNN, Decision Trees, Random Forest)
*   **Environment:** `Jupyter Notebook`

## 🔍 The Investigation (Workflow & EDA)
1.  **📥 Data Ingestion:** Loaded via `sklearn.datasets`.
2.  **📊 EDA:** Pair plots & heatmaps revealed that **Petal dimensions** are much stronger predictors than Sepal dimensions.
3.  **⚙️ Preprocessing:** Standard scaling and an 80/20 stratified train-test split.
4.  **🧠 Modeling:** Trained and evaluated multiple algorithms.

## 💡 "Aha!" Moments
*   **Feature Importance:** EDA proved that *Sepal Width* is the weakest predictor. Dropping it barely impacts accuracy.
*   **Model Behavior:** Decision Trees are highly interpretable but prone to slight overfitting compared to the smoother boundaries of SVMs.

---

## 📈 Results & Performance

**📊 Dataset:** `150 samples` | `6 columns` | `100% clean` (0 missing, 0 duplicates)

**🏆 Model Accuracy Comparison:**
| Model | Test Accuracy |
| :--- | :---: |
| **Logistic Regression** 🥇 | **100.00%** |
| KNN / Decision Tree / SVM | 100.00% |
| Random Forest (Tuned) | 96.67% |
| Dummy Classifier (Baseline) | 33.33% |

**🔧 Hyperparameter Tuning (Random Forest):**
*   **Best Params:** `{'max_depth': None, 'min_samples_split': 2, 'n_estimators': 50}`
*   **Best CV Score:** `99.17%` | **Test Accuracy:** `96.67%`

**🎯 Conclusion:** 
While multiple models achieved perfect accuracy, **Logistic Regression** was selected as the final best model for its optimal balance of 100% performance, simplicity, and interpretability.

---

## 👨‍💻 About the Author

**Ojoawo Micheal**  
*Aspiring Renewable Energy & Energy Systems Engineer* 🌍⚡

Passionate about sustainable solutions and optimizing energy systems. I love turning raw data into actionable insights and am always eager to apply data science and engineering principles to real-world energy challenges!

🔗 **Let's Connect:**
*   [LinkedIn](#) *https://www.linkedin.com/in/micheal-ojoawo/*
*   [GitHub](#) *https://github.com/micheal15-0*
*   ✉️ Email: *ojoawo-mic@upf.ac.ma*

---
