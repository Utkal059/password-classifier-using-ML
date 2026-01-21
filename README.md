# 🔐 Password Strength Classification using Machine Learning

This project implements a **Machine Learning–based password strength classifier** that predicts whether a password is **Weak**, **Medium**, or **Strong**.  
It uses a real-world dataset and applies **text feature extraction** with a supervised ML model.

---

## ✨ Key Highlights
- Real dataset (Kaggle compatible)
- Automatic CSV file detection in Google Colab
- Character-level text analysis
- Accurate classification of password strength
- Beginner-friendly and easy to extend

---

## ⚙️ Working Principle
1. Password data is loaded from a CSV file  
2. Passwords are transformed into numeric features using **TF-IDF (character analyzer)**  
3. A **Logistic Regression** classifier is trained  
4. Model accuracy is evaluated on test data  
5. User input is classified in real time  

---

## 📁 Repository Structure
password-strength-ml/
│
├── dataset.csv
├── password_strength_ml.py
├── README.md

---

## 📊 Dataset Description
- Source: Kaggle Password Strength Dataset
- Format: CSV file
- Columns:
  - `password` – Password text
  - `strength` – Password strength label

### Label Mapping
| Value | Strength |
|-----|---------|
| 0 | Weak |
| 1 | Medium |
| 2 | Strong |

---

## ▶️ Execution Steps
1. Upload the CSV file in Google Colab  
2. Install dependencies:
3.Run the script and enter a password when prompted

