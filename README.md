# 📱 Mobile Battery Drain Predictor

A Machine Learning Lab Midterm Project that predicts mobile battery drain based on user behavior patterns such as screen usage, brightness, running applications, WiFi usage, and battery saver mode.

---

# 📌 Project Overview

The goal of this project is to understand the fundamentals of Machine Learning by:

- Creating a custom synthetic dataset
- Performing Exploratory Data Analysis (EDA)
- Applying supervised learning algorithms
- Comparing model performance
- Interpreting results and correlations

This project focuses on simplicity, interpretability, and understanding core ML concepts.

---

# ⚙️ Features Used

| Feature | Description |
|---|---|
| `screen_time` | Time spent using device (hours) |
| `brightness` | Screen brightness percentage |
| `apps_running` | Number of active applications |
| `wifi_on` | WiFi status (0 = OFF, 1 = ON) |
| `battery_saver` | Battery saver mode (0 = OFF, 1 = ON) |

### 🎯 Target Variable
| Variable | Description |
|---|---|
| `battery_drain` | Predicted battery consumption (%) |

---

# 🧪 Dataset

A synthetic dataset was generated using Python and NumPy.

The dataset simulates realistic mobile usage behavior:
- Increased screen time increases battery drain
- More running apps increase battery usage
- Battery saver reduces battery consumption
- Random noise was added to simulate real-world variability

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset summary statistics
- Correlation matrix
- Scatter plots
- Distribution plots

### 🔍 Key Insights
- Screen time showed the strongest positive correlation with battery drain
- Battery saver showed a negative correlation
- WiFi showed weaker correlation due to smaller impact and noise

---

# 🤖 Machine Learning Models Used

## 1️⃣ Linear Regression
- Works well for linear relationships
- Easy to interpret

## 2️⃣ Decision Tree Regressor
- Captures non-linear patterns
- May overfit on small datasets

---

# 📈 Evaluation Metrics

The models were evaluated using:

- **MAE (Mean Absolute Error)**
- **R² Score**

---

# 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📂 Project Structure

```bash
battery-drain-ml/
│
├── Battery_Drain_Predictor.ipynb
├── README.md
├── requirements.txt
```

---

# ▶️ How to Run

## 1️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

## 2️⃣ Run the notebook

Open:

```bash
Battery_Drain_Predictor.ipynb
```

Run all cells sequentially.

---

# 📌 Results

- Linear Regression performed well because the dataset had mostly linear relationships
- Decision Tree captured patterns differently but showed possible overfitting
- Battery saver successfully introduced inverse correlation into the dataset

---

# 🚀 Future Improvements

- Use real-world battery usage data
- Add more device-related features
- Apply advanced ML algorithms
- Add interactive visualizations

---

# 👨‍💻 Author

**[ANAS ARIF - 67579]**  
Machine Learning Lab Midterm Project

---

# 📖 Learning Outcome

This project helped in understanding:
- Dataset generation
- Data preprocessing and EDA
- Supervised learning
- Model comparison
- Performance evaluation
- Interpretation of ML results
