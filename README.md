# NeuroBalance
ML-Based Employee Wellness Predictor – predicts employee wellness and visualizes stress/work-life balance
# NeuroBalance

**ML-Based Employee Wellness Predictor**

---

## Project Overview
NeuroBalance predicts the **wellness level of employees** as `High`, `Medium`, or `Low` using machine learning.  
It analyzes employee features such as **work hours, sleep hours, tasks completed, stress level, and job satisfaction** to help HR monitor employee well-being and improve productivity.

---

## Why This Project is Useful
- Helps HR identify employees with **high stress or low wellness**  
- Enables **proactive interventions** to improve employee satisfaction  
- Visualizes **trends in work-life balance**  
- Saves **time and effort** compared to manual analysis  

---

## What I Did
1. Created a **synthetic employee dataset** with relevant features  
2. Preprocessed data using **Python and Pandas**  
3. Scaled features using **StandardScaler**  
4. Trained a **Random Forest Classifier** to predict wellness level  
5. Visualized data using **Matplotlib and Seaborn**  
6. Saved the **trained model and scaler** as `.pkl` files  
7. Created a **Colab notebook** to run the project and make predictions for new employees  

---

## Problems Faced & Solutions

| Problem | Solution |
|---------|---------|
| No real dataset available | Created **synthetic employee dataset** |
| String/categorical values caused errors | Converted strings to **numeric codes** |
| StandardScaler warning on new data | Applied **same scaler used in training** to new input |
| HR cannot open `.pkl` files | Used `.pkl` in Colab to **show predictions directly**, without opening the file |

---

## Project Features
- Predicts employee wellness: **High / Medium / Low**  
- Graphs to visualize **work-life balance, stress trends, and wellness distribution**  
- Allows HR to **test predictions for new employees**  
- Built with **Python, Pandas, Scikit-learn, Matplotlib, and Seaborn**  

---

## How to Use
1. Open `NeuroBalance.ipynb` in **Google Colab**  
2. Run all cells to:
   - Load and inspect the dataset  
   - Visualize graphs  
   - Load trained model (`neuro_model.pkl`) and scaler (`scaler.pkl`)  
   - Predict wellness level for new employee data  

---

## Files in the Repository
- `NeuroBalance.ipynb` → Notebook with code and outputs  
- `employee_data.csv` → Synthetic dataset of employees  
- `neuro_model.pkl` → Trained ML model  
- `scaler.pkl` → StandardScaler used for feature normalization  
- `README.md` → Project description  

---

## Tools & Libraries
- Python 3.x  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  
- Google Colab  

---

## Author
**Pasam Baby**  
Final Year B.Tech (AI & DS)  
GitHub: [https://github.com/pasam-baby](https://github.com/pasam-baby)
