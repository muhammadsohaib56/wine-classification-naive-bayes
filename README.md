# 🍷 Wine Classification using Naive Bayes


````markdown

This project applies the **Naive Bayes Classifier** to predict the class of a wine based on its chemical features. It uses the well-known `Wine dataset` from `scikit-learn`, which includes measurements like alcohol, flavanoids, and color intensity.

---

## 📊 Dataset

The **Wine dataset** contains:
- 178 samples of wine
- 13 numerical features (e.g., alcohol, malic acid, ash, etc.)
- 3 classes representing different cultivars of wine

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib` / `seaborn` (optional for visualization)

---

````
## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/wine-classification-naive-bayes.git
   cd wine-classification-naive-bayes
   ```
2. Launch the notebook:

   ```bash
   jupyter notebook Wine-Prediction-NB.ipynb
   ```

3. Or run a Python script (if provided):

   ```bash
   python wine_predictor.py
   ```

---

## 🧠 Model Used

* **Gaussian Naive Bayes** from `sklearn.naive_bayes`
* Trained using 13 chemical features
* Outputs one of the 3 wine classes

---

## 📈 Evaluation

* Train/test split using `train_test_split`
* Accuracy score
* Optional confusion matrix or classification report

---

## ✅ Sample Output

```python
model.predict([[13.0, 2.0, 2.5, ..., 3.0]])  # Output: [1]
```

* Predicts the wine class based on input features.

---

## 📂 File Structure

```
wine-classification-naive-bayes/
│
├── Wine-Prediction-NB.ipynb         # Main notebook
├── README.md                        # Project documentation
```

---

## 🤝 Contributing

Improvements like advanced feature scaling, alternate models (e.g., SVM, Random Forest), or visualization are welcome.

---

## 📜 License

[MIT License](LICENSE)

---


