
# Calgary Crime Data Analysis and Neural Network Prediction

## 📌 Overview

This project focuses on analyzing **Calgary’s community crime data (2018–2024)** and building a **neural network model** to predict future crime counts.
It combines **data preprocessing, exploratory data analysis (EDA), and LSTM-based deep learning models** to uncover insights and forecast crime patterns.

---

## 📊 Dataset

The dataset is obtained from the **City of Calgary’s official open data portal**.
It contains **70,661 records** with the following columns:

| Column           | Description                                         |
| ---------------- | --------------------------------------------------- |
| `Community Name` | The name of the community in Calgary                |
| `Category`       | Type of crime (e.g., Theft, Assault, Break & Enter) |
| `Crime Count`    | Number of crimes in a given month                   |
| `Year`           | Year of occurrence                                  |
| `Month`          | Month of occurrence                                 |

---

## 🔎 Project Workflow

1. **Data Loading & Cleaning** – Inspect missing values, correct data types, handle categorical features.
2. **Exploratory Data Analysis (EDA)** –

   * Community-wise crime distribution
   * Crime categories analysis
   * Temporal analysis (yearly and monthly trends)
   * Visualization of patterns and relationships
3. **Preprocessing for Modeling** – Label encoding, sequence creation for time-series modeling.
4. **Model Development** –

   * Implemented an **LSTM (Long Short-Term Memory)** neural network
   * Optimized with dropout layers and Adam optimizer
5. **Training & Evaluation** –

   * Trained over 100 epochs
   * Achieved a **test loss \~4.89 (MSE)**
   * Visualized actual vs predicted values and residuals

---

## 🧠 Technologies Used

* **Python**
* **Pandas, NumPy** – Data handling
* **Matplotlib, Seaborn** – Data visualization
* **Scikit-learn** – Preprocessing, train-test split
* **TensorFlow / Keras** – LSTM model building and training

---

## 📈 Results

* Identified **top crime-prone communities** (e.g., Beltline, Forest Lawn).
* Found **theft-related crimes** as the most common category.
* Built an **LSTM model** capable of forecasting monthly crime counts with good accuracy.

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/Calgary-Crime-Prediction.git
   cd Calgary-Crime-Prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or script:

   ```bash
   jupyter notebook Calgary_Crime_Data_Analysis_and_Neural_Network_Prediction.ipynb
   ```

---
