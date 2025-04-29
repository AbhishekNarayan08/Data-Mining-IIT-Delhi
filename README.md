# 📊 Data Mining – IIT Delhi

This repository contains coursework from the Data Mining course at IIT Delhi. You’ll find three Jupyter notebooks covering core data mining techniques: Apriori, FP Growth, and Multiclass Classification.

---

## 📁 Contents

- `apriori.ipynb` – **Apriori Algorith for Association Rule Mining**  
- `FP Tree.ipynb` – **FP Growth Algorithm for Association Rule Mining**
- `Multiclass Classification.ipynb` – **Multiclass Classification**  

---

## 📌 Assignment Descriptions

### 1. Association Rule Mining (Apriori & FP-Growth)  
- **Apriori**: Iteratively builds candidate itemsets and prunes based on minimum support, then generates high-confidence rules. Good for small to medium datasets but can be slow when itemset combinations explode.  
- **FP-Growth**: Builds a compact prefix-tree (FP-tree) of transactions and mines frequent patterns by recursively extracting conditional trees. Generally faster than Apriori, especially on large or dense datasets.

### 2. Multiclass Classification  
Implements supervised learning on datasets with more than two target classes. Explores algorithms like **Decision Trees**, **Random Forests**, and **k-Nearest Neighbors**, evaluates with metrics such as accuracy, precision/recall per class, and macro-averaged F1 score.
