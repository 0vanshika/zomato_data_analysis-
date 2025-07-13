
# 🍽️ Zomato Data Cleaning – Jupyter Notebook


This repository contains a Jupyter Notebook for **cleaning and preprocessing Zomato restaurant data**. The dataset contains detailed information about restaurants, cuisines, ratings, and costs. This notebook transforms the messy dataset into a clean and analysis-ready format.

---

## 📌 Features

✅ Drops irrelevant columns  
✅ Renames confusing column names  
✅ Cleans cost and rating fields  
✅ Handles missing data  
✅ Saves cleaned dataset for analysis

---

## 📁 Files in This Repo

| File Name                        | Description                                      |
|----------------------------------|--------------------------------------------------|
| `zomato_data_cleaning.ipynb`     | Jupyter Notebook for cleaning the dataset        |
| `zomato_data_anaylsis_cleaned.csv` | Output CSV file (after running the notebook)     |
| `zomato (2).csv` *(required)*    | Original dataset file *(not included here)*      |

---

## 🧼 Cleaning Steps Performed

1. **Import Libraries**  
2. **Load Dataset**  
3. **Drop Irrelevant Columns**  
4. **Rename Columns for Clarity**  
5. **Remove Missing Values**  
6. **Clean Cost Data** (remove commas, divide by 2 for per person)  
7. **Clean Rating Data** (handle NEW, '-', convert to float)  
8. **Save to Cleaned CSV**

---

## 🚀 How to Run This Notebook

### 🔧 Prerequisites

Install the necessary Python packages:
```bash
pip install pandas numpy
```

### ▶️ Steps

1. Clone this repository:
```bash
git clone https://github.com/your-username/zomato-data-cleaning.git
cd zomato-data-cleaning
```

2. Add the raw dataset file:
> Make sure `zomato (2).csv` is placed in the same directory.

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open and run all cells in `zomato_data_cleaning.ipynb`

---

## 📊 What's Next?

🔍 Perform Exploratory Data Analysis (EDA)  
📈 Create visualizations for cuisines, ratings, cost etc.  
🧠 Build ML models for price prediction or restaurant recommendation  

---

## 🧑‍💻 Author

**Vanshika Garg**  
📫 For any queries or collaborations, feel free to connect!

---

## 📝 License

This project is licensed under the **MIT License**.  
Feel free to fork, use, and modify the code for your own projects.

---
