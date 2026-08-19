# PM2.5_AirQuality

A Machine Learning project focused on predicting **PM2.5 (Particulate Matter 2.5)** concentrations using different regression approaches. The project explores both **from-scratch neural network implementation** and **built-in machine learning models**, providing a practical comparison of different approaches to regression.

## 📌 Overview

PM2.5 refers to fine particulate matter with a diameter of **2.5 micrometers or smaller**. Because these particles can remain suspended in the atmosphere and penetrate deeply into the respiratory system, monitoring and predicting PM2.5 levels is an important part of air-quality analysis.

This project experiments with multiple Machine Learning techniques to model PM2.5 concentrations and understand how different regression architectures perform on the dataset.

The repository contains implementations using:

* 🧠 Multi-Layer Perceptron (MLP) from scratch
* 🤖 Scikit-learn `MLPRegressor`
* 📈 Linear Regression
* 🔗 Keras Sequential model

---

## 🎯 Objectives

The main objectives of this project are:

* Analyze PM2.5 air-quality data.
* Understand the relationship between input features and PM2.5 concentration.
* Implement a neural network from scratch.
* Compare custom implementations with built-in ML models.
* Experiment with different regression architectures.
* Understand the practical workflow of training and evaluating regression models.

---

## 🧠 Models Implemented

### 1. Multi-Layer Perceptron From Scratch

The project includes an implementation of an MLP without relying on a high-level neural-network training API.

This helps demonstrate the underlying concepts involved in neural-network training, including:

* Forward propagation
* Activation functions
* Loss calculation
* Backpropagation
* Gradient-based optimization
* Parameter updates

📓 Notebook:

`mlp_from_scratch_on_pm2_5_Dataset.ipynb`

---

### 2. Scikit-learn MLPRegressor

A built-in neural-network regression model from Scikit-learn is used to provide a more convenient implementation of an MLP.

📓 Notebook:

`Using_inbuilt_mlpRegressor.ipynb`

This provides a useful comparison between implementing an MLP manually and using an established machine-learning library.

---

### 3. Linear Regression

Linear Regression is used as a baseline regression approach.

📓 Notebook:

`Using_inbuilt_model_LinearRegression.ipynb`

Using a simpler model as a baseline makes it easier to understand whether a more complex neural-network architecture provides additional predictive value.

---

### 4. Keras Sequential Model

A neural-network architecture is also explored using the Keras Sequential API.

📓 Notebook:

`Using_sequential.ipynb`

This demonstrates how the same general regression problem can be approached using a high-level deep-learning framework.

---

## 📂 Repository Structure

```text
PM2.5_AirQuality/
│
├── LICENSE
├── README.md
├── encountered.txt
│
├── mlp_from_scratch_on_pm2_5_Dataset.ipynb
├── Using_inbuilt_mlpRegressor.ipynb
├── Using_inbuilt_model_LinearRegression.ipynb
└── Using_sequential.ipynb
```

---

## 🛠️ Technologies Used

| Technology         | Purpose                       |
| ------------------ | ----------------------------- |
| Python             | Core programming language     |
| NumPy              | Numerical computation         |
| Pandas             | Data manipulation             |
| Matplotlib         | Data visualization            |
| Scikit-learn       | Machine Learning models       |
| TensorFlow / Keras | Neural-network implementation |
| Jupyter Notebook   | Experimentation and analysis  |

---

## ⚙️ Project Workflow

```text
PM2.5 Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Preparation
      │
      ├───────────────┐
      ▼               ▼
Linear Regression    MLP Models
                      │
             ┌────────┴────────┐
             ▼                 ▼
       MLP From Scratch   MLPRegressor
             │                 │
             └────────┬────────┘
                      ▼
              Keras Sequential
                      │
                      ▼
             Model Evaluation
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Ishany0/PM2.5_AirQuality.git
cd PM2.5_AirQuality
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any of the notebooks and run the cells sequentially.

---

## 📊 Experiments

The project is structured as a progression from simpler to more advanced approaches:

1. **Linear Regression**
   Establishes a simple baseline.

2. **MLP From Scratch**
   Demonstrates the mathematical and algorithmic foundations of neural networks.

3. **Scikit-learn MLPRegressor**
   Provides a production-oriented implementation using a standard ML library.

4. **Keras Sequential Model**
   Explores neural-network construction using a deep-learning framework.

This progression makes the project useful for understanding not only **how to use ML models**, but also **what happens underneath a neural network implementation**.

---

## 🔍 Key Learning Outcomes

Through this project, the following concepts are explored:

* Regression problems
* Feature preprocessing
* Neural-network architecture
* Forward propagation
* Backpropagation
* Gradient-based optimization
* Model training
* Prediction
* Comparing traditional ML with neural networks
* Implementing ML algorithms from scratch
* Using Scikit-learn and TensorFlow/Keras

---

## 📈 Future Improvements

Possible extensions to the project include:

* [ ] Perform detailed Exploratory Data Analysis (EDA)
* [ ] Add additional regression algorithms such as Random Forest and Gradient Boosting
* [ ] Perform systematic hyperparameter tuning
* [ ] Compare models using MAE, MSE, RMSE and R²
* [ ] Add cross-validation
* [ ] Perform feature engineering
* [ ] Add visual comparisons between predicted and actual PM2.5 values
* [ ] Build a real-time PM2.5 prediction application
* [ ] Deploy the best-performing model as a web application

---

## 📚 Project Motivation

This project was developed to gain practical experience with **Machine Learning regression and neural networks** while applying these concepts to an environmental problem.

Rather than relying exclusively on high-level APIs, the project also explores how an MLP can be constructed from fundamental components, making it useful for understanding the mechanics behind neural-network-based regression.

---

## 👤 Author

**Ishanya**

GitHub: [Ishany0](https://github.com/Ishany0)

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more information.

---

⭐ If you find this project useful, consider giving it a star!
