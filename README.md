# Lab 1: Decoding the Game – Data Wrangling with Cricket JSON  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/KP-AI-ML-Labs/Lab1-Data-Wrangling/blob/main/g_Lab1_S.ipynb)

---

## 📖 Story Point  
Before we can predict, we must understand. Our first task is to make sense of the complex data feed from our source.

---

## 🎓 Mapping to Lecture  
- **Topic:** Data Preprocessing  
- **Python Libraries:** `json`, `pandas`  
- **Category:** Data Preprocessing  

---

## 🧪 In-Class Practical  

**Objective:**  
Load the nested JSON data, understand its hierarchical structure, and extract key information into a flat, usable format.  

**Tasks (Student Notebook):**  
1. Load the `json_response.json` file  
2. Navigate the nested structure to access the `score` object  
3. Extract the `batsmen` list from the **first innings** (`innings[0]`)  
4. Create a Pandas DataFrame from the extracted `batsmen` list  
5. Perform basic data cleaning: check for null values and data types  

---

## 🏡 Home Task  
- Expand on the in-class work by extracting the `bowlers` list from the first innings  
- Create a second DataFrame for the bowlers  
- Write a function that takes an `innings` object as input and returns two DataFrames: one for batsmen and one for bowlers  

---

## ✅ Deliverable  
A Jupyter Notebook with a clean DataFrame of first-innings batting performance, saved as a `.csv` file.  

---

## ⚙ Requirements  
Install required libraries:  
`!pip install -r requirements.txt`


