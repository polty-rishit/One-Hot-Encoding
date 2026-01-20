# One-Hot Encoding

## 📌 Overview
This repository contains a Jupyter Notebook that demonstrates the use of **One-Hot Encoding**, one of the most commonly used techniques for converting **categorical data** into a numerical format suitable for machine learning models.

Categorical variables often cannot be directly used in mathematical models. One-Hot Encoding solves this problem by representing each category as a binary (0 or 1) vector, ensuring that no unintended ordinal relationship is introduced.

---

## 🧠 What is One-Hot Encoding?
One-Hot Encoding transforms a categorical feature with *N* unique categories into *N* new binary features.  
Each category is represented by a vector where:
- `1` indicates the presence of the category
- `0` indicates its absence

### Example:
| Color | Red | Blue | Green |
|------|-----|------|-------|
| Red  | 1   | 0    | 0     |
| Blue | 0   | 1    | 0     |
| Green | 0  | 0    | 1     |

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – for data manipulation and encoding
- **NumPy** – for numerical operations
- **Jupyter Notebook**

---

## 📦 Installation
Make sure Python is installed on your system. Install the required libraries using:

```bash
pip install pandas numpy
