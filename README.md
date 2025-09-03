# Breast Cancer Detection with Deep Neural Networks (DNN)

## 📌 Project Overview

Breast cancer is one of the most common cancers among women worldwide, and **early detection** is critical for improving survival rates. This project implements a **Deep Neural Network (DNN)** to classify tumors as **benign** or **malignant** using features from the **Breast Cancer Wisconsin dataset**.

The model is trained and validated using **K-Fold Cross-Validation** to ensure robustness and reliability.

---

## 📂 Dataset

The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Dataset** from the **UCI Machine Learning Repository**.

* **Features (30):** Real-valued attributes such as radius, texture, smoothness, symmetry, etc.
* **Target (1):**

  * `0` → Benign
  * `1` → Malignant

---

## ⚙️ Features of the Project

* Data preprocessing & feature scaling with **StandardScaler**
* Deep Neural Network with:

  * Dense layers
  * Dropout for regularization
  * Adam optimizer
* **5-Fold Cross-Validation** for reliable evaluation
* Visualization of training/validation accuracy & loss

---

## 🏗️ Model Architecture

* **Input Layer:** 30 features
* **Hidden Layers:** Multiple Dense layers with ReLU activation
* **Dropout Layers:** Prevent overfitting
* **Output Layer:** Sigmoid activation for binary classification

---

## 🚀 Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/breast-cancer-dnn.git
cd breast-cancer-dnn
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Requirements

Main libraries used:

* `numpy`
* `pandas`
* `matplotlib`
* `scikit-learn`
* `tensorflow` / `keras`

---

## 🔍 How to Run

Run the Jupyter notebook:

```bash
jupyter notebook "Breast Cancer Detection with DNN.ipynb"
```

Steps inside notebook:

1. Load dataset
2. Preprocess & scale features
3. Build the DNN model
4. Train using 5-fold cross-validation
5. Evaluate average accuracy
6. Visualize performance

---

## 📊 Results

* **Cross-validation Accuracy:** \~95% (average across folds)
* **Key Insights:**

  * DNN generalizes well across folds
  * Dropout reduces overfitting
  * Training & validation curves show stable learning

---

## 📈 Visualizations

* Accuracy & Loss plots for training/validation (last fold)
* Performance comparison across K-folds

---

## 📌 Future Improvements

* Hyperparameter tuning (learning rate, batch size, layers)
* Experiment with advanced architectures (CNNs on tabular data, AutoML)
* Deploy as a **Flask/Streamlit app** for real-time classification

---

## 🤝 Contributing

Contributions are welcome! You can improve preprocessing, optimize models, or work on deployment.

---

## 📧 Contact

👩‍💻 **Akanksha Sawant**

* 📍 Pune, India
* 💼 [LinkedIn]([https://www.linkedin.com](https://www.linkedin.com/in/akanksha-sawant-29260226a/))
* 🖥️ [GitHub](https://github.com/AkankshaASawant)

---
