
## **Stock Price Predictor (Tkinter App + Optional Google Colab)**

### 📌 **Overview**

This project predicts the **next day's closing stock price** using **Machine Learning (Linear Regression)** and provides a **Tkinter GUI application** for easy interaction.

* **Tkinter Desktop App** → Main application (predict stock price & show graph)
* **Google Colab (Optional)** → For users who want to check or clean their dataset before using the app

---

## **1️⃣ Tkinter Desktop App (Main Application)**

### **Features**

✔️ Predict next day's closing price using Linear Regression
✔️ Upload any stock dataset via GUI
✔️ Auto-cleaning of data (no need for Colab)
✔️ Actual vs Predicted Closing Prices graph

---

### **Requirements**

1. Install Python 3
2. Install required libraries:

```bash
pip install pandas scikit-learn matplotlib
```

---

### **Project Structure**

```
StockPricePredictor/
│
├── stock_predictor.py             # Main GUI + ML code
├── HistoricalQuotes.csv           # Sample dataset (raw or cleaned)
├── Colab_Dataset_Checking.ipynb   # (Optional) Google Colab notebook
└── README.md                       # Project documentation
```

---

### **How to Run the Desktop App**

1️⃣ Open **Command Prompt (CMD)** and navigate to Desktop:

```bash
cd Desktop
```

2️⃣ Enter the project folder:

```bash
cd StockPricePredictor
```

3️⃣ Run the application:

```bash
python stock_predictor.py
```

4️⃣ GUI will open:

* Click **Upload CSV**
* Select your dataset (raw or cleaned)
* A popup will display the **Predicted Next Day's Closing Price**
* An Actual vs Predicted graph will also be shown

---

### **Sample Output**

**Popup Window:**

```
Predicted Next Day's Closing Price: $184.25
```

**Graph:**

* Blue Line → Actual Closing Prices
* Red Dashed Line → Predicted Closing Prices

---

## **2️⃣ Google Colab (Optional - Dataset Checking)**

This step is **not required**, but if you want to check your dataset before using it in the app, open the provided **Colab notebook**:

```
Colab_Dataset_Checking.ipynb
```

➡️ This file already contains all the necessary commands to:

* Check dataset shape, columns, missing values & datatypes
* Clean dollar signs and column inconsistencies
* Save a cleaned CSV for use in the Tkinter App

Once you’ve cleaned the dataset, download the new CSV and use it with the desktop application.

---

### **Future Enhancements**

* Direct live data fetching via `yfinance`
* Add more robust models (Random Forest, XGBoost)
* Multi-day forecasting feature

---

### **Author**

👤 **Abdul Rehman**
💡 Contributions & forks are welcome!

---
