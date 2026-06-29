# 📊 Global Education Statistics Dashboard

## 🔍 Project Overview

This project is an interactive data visualization dashboard built using **Dash** and **Plotly**.
It provides insights into global education statistics such as literacy rates, unemployment, birth rates, and gender gaps across different countries.

The dashboard allows users to:

* Filter data by country
* Select number of top countries (Top N)
* Switch between different metrics
* Explore multiple chart types (bar, scatter, bubble, histogram, etc.)

The goal of this project is to make education-related data **interactive, clear, and easy to analyze**.

---

## 📁 Dataset Description

The dataset used in this project contains global education and demographic indicators.

**Main Features:**

* `country` → Country name
* `literacy_rate` → Overall literacy rate (%)
* `literacy_male` → Male literacy rate
* `literacy_female` → Female literacy rate
* `literacy_gap` → Difference between male & female literacy
* `unemployment_rate` → Unemployment percentage
* `birth_rate` → Birth rate
* `primary_enrollment` → Primary education enrollment
* `tertiary_enrollment` → Higher education enrollment
* `g2_reading` → Reading performance score

📌 The dataset is loaded from a local CSV file in the project. 

---

## 👥 Team Members

* Member 1 & 2: Nadia Mohammed Ibrahim & Haidy Hossam-Eldeen Mohammed --->  Comparison Charts 
* Member 3: Malak Waleed Youssef ---> Relationship Charts
* Member 4: Tasneem Tarek Mohammed ---> Distribution  Charts
* Member 5: Menna-Allah Rabee Mohammed ---> Preprocessing +Time-Series Charts + GUI

---

## ⚙️ Technologies Used

* Python
* Dash
* Plotly
* Pandas

---

## 📊 Dashboard Features

The dashboard includes multiple interactive charts:

* Column Chart → Literacy gap comparison
* Bar Chart → Lowest countries by selected metric
* Stacked Charts → Gender distribution
* Clustered Charts → Compare multiple metrics
* Scatter Plot → Literacy vs Reading score (with outliers)
* Bubble Chart → Multi-variable visualization
* Histogram → Distribution analysis
* Box Plot → Tertiary enrollment spread
* Violin Plot → Birth rate distribution
* Line Chart → Ranked trends
* Area Chart → Literacy progression

---

## ▶️ How to Run the Project

### 1. Install Dependencies

Make sure you have Python installed, then run:

```bash
pip install dash pandas plotly
```

---

### 2. Update Dataset Path

Edit the dataset path in the code if needed:

```python
df = pd.read_csv("path_to_your_dataset.csv")
```

---

### 3. Run the App

```bash
python app.py
```

---

### 4. Open in Browser

Go to:

```
http://127.0.0.1:8051/
```

---

## 💡 Notes

* Make sure the dataset file exists in the correct path
* If port 8051 is busy, you can change it in the code
* The dashboard is fully interactive and updates dynamically

---

## 🚀 Future Improvements

* Add more filters (region, income level)
* Connect to real-time data sources
* Deploy online (Render / Heroku)
* Improve UI/UX design

---
