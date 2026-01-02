# CA-4: Neural Networks & Deep Learning

This assignment focuses on designing, training, and evaluating **deep learning models**
for different data modalities, including tabular data, images, and time series.
The project covers **MLP, CNN, and RNN-based architectures**, emphasizing both
modeling and performance analysis.

---

## What This Project Does

In this project, I implemented multiple neural network models to solve
classification and regression problems across three distinct tasks.
The assignment emphasizes:

- Data preprocessing and feature engineering
- Neural network architecture design
- Model training, evaluation, and comparison
- Interpreting model behavior and performance

---

## 📂 Project Files and Structure

| Folder / File | Purpose                                               |
| ------------- | ----------------------------------------------------- |
| `task1/`    | Match outcome prediction using MLP                    |
| `task2/`    | Image classification using CNNs and transfer learning |
| `task3/`    | Time-series forecasting using RNN and LSTM            |
| `bonus.md`  | Bonus theoretical analysis (CNN parameters)           |
| `readme.md` | Assignment description                                |
| `*.ipynb`   | Jupyter notebooks for each task                       |

---

## Implemented Tasks (Detailed)

### 🔹 Task 1 – Football Match Outcome Prediction (MLP)

- Performed data preprocessing, exploratory analysis, and feature standardization
  on historical football match results
- Developed a **multi-layer perceptron (MLP) classifier** to predict match outcomes
  (home win, draw, away win)
- Applied **class balancing techniques** to address label imbalance
- Evaluated model performance on held-out **World Cup matches**
- Simulated the **2022 World Cup tournament** using model-based match predictions
- Engineered team-strength statistics from simulated outcomes

---

### 🔹 Task 2 – Flower Image Classification (CNN & Transfer Learning)

- Loaded a multi-class flower image dataset
- Applied data preprocessing and **image augmentation**
- Implemented:
  - A **custom CNN architecture**
  - A **transfer learning model using ResNet-50**
- Trained models using **staged fine-tuning strategies** to adapt pretrained features
- Evaluated performance using:
  - Accuracy, precision, recall, and F1-score
  - ROC curves
  - Confusion matrices

---

### 🔹 Task 3 – Bitcoin Price Movement Prediction (RNN & LSTM)

- Performed time-series preprocessing and exploratory analysis on historical
  Bitcoin **OHLCV** data
- Engineered supervised learning sequences to predict **next-day percentage price movement**
- Trained and validated:
  - Recurrent Neural Networks (RNN)
  - Long Short-Term Memory networks (LSTM)
- Used **sliding-window inputs** with different lookback horizons
- Evaluated prediction performance using regression metrics and error trend plots
- Benchmarked **RNN vs. LSTM** models and analyzed the impact of lookback window size

---

## How to Run the Project

```bash
git clone https://github.com/nelyasi71/Data-Science-Course-spring2025.git
cd Data-Science-Course-spring2025/CA-4
```
