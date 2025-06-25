
# 🧠 Bayes to the Future: Predicting Heart Disease with Data!

Welcome to **MediMystery Labs**! As a Data Detective, your mission is to predict heart disease risk using a Bayesian Network trained on simulated patient data. This project demonstrates how to clean, preprocess, and model medical data using probabilistic reasoning with `pgmpy`.

---

## 📁 Project Structure

```

bayes-heart-disease/
├── heart\_disease.csv
├── Bayes\_Heart\_Disease\_Predictor.ipynb
├── README.md
├── requirements.txt
└── .gitignore

```

---

## 🔍 What This Project Does

- ✅ Cleans and normalizes medical patient records
- ✅ Discretizes numeric variables (age, cholesterol, heart rate)
- ✅ Builds a Bayesian Network with custom structure:
```

age → fbs → target → chol, thalach

````
- ✅ Trains the model using Maximum Likelihood Estimation (MLE)
- ✅ Uses inference to answer diagnostic questions
- ✅ Visualizes results with histograms and bar charts

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
 ```bash
 git clone https://github.com/your-username/bayes-heart-disease.git
 cd bayes-heart-disease
````

2. **Install Required Packages**
   *(Create a virtual environment if desired)*

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**

   ```bash
   jupyter notebook Bayes_Heart_Disease_Predictor.ipynb
   ```

---

## 🧪 Sample Outputs

### 📊 Inference Result

**P(Heart Disease | Age = 'medium'):**

```
+-------------+---------------+
| target      |   phi(target) |
+=============+===============+
| target(0.0) |        0.4578 |
| target(1.0) |        0.5422 |
+-------------+---------------+
```

### 💉 Cholesterol Distribution (Heart Disease = 1.0)

![image](https://github.com/user-attachments/assets/baf819ac-0c17-4d98-9910-cd41744cbaad)

---

## 📦 Requirements

```
pandas
matplotlib
seaborn
scikit-learn
pgmpy==0.1.23
```

---

## 📌 Dataset

Simulated heart disease data from UCI repository (used via this shortened link):
[Download heart\_disease.csv](https://bit.ly/3T1A7Rs)

---

## 🙌 Credits

Created by **Uday Kiran** as part of a medical AI data modeling challenge using Python and Bayesian Networks.

---

## 📬 Contact

Feel free to connect or contribute via GitHub!

