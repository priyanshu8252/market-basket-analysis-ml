# Market Basket Analysis for Retail Optimization

## 📌 Project Overview
This project implements **Association Rule Mining (Market Basket Analysis)** on retail transaction data to discover deep behavioral purchasing patterns. Utilizing the **Apriori Algorithm**, the system processes transaction history to uncover strong product relationships (e.g., *"Customers who purchase a Laptop are highly likely to buy a Wireless Mouse and HDMI Cable in the same transaction"*). 

These insights are designed to assist retail managers in optimizing store layouts, designing targeted cross-selling strategies, and improving automated product recommendation systems.

## 🛠️ Features & Methodology
- **Data Pipeline:** Preprocessed raw transaction streams into a one-hot encoded binary format suitable for transaction mining.
- **Frequent Itemset Mining:** Executed the **Apriori Algorithm** using the `mlxtend` framework to isolate high-frequency purchasing behaviors based on strict Support metrics.
- **Association Rule Generation:** Extracted strategic rules and measured their reliability using **Confidence** and **Lift** metrics to isolate true purchasing patterns from random coincidences.
- **Data Visualization:** Generated scatter plots mapping *Support vs. Confidence*, color-coded by *Lift Strength*, to allow clear interpretation of rule groups.

## 📁 Repository Structure
- `Market_Basket_Analysis.ipynb` - The complete Jupyter Notebook housing the generation pipeline, core calculations, predictive rules, and data charts.

## 📊 Key Insights Extracted
- **Support:** Identified the core volume of popular product bundles.
- **Confidence:** Calculated the conditional probability of a secondary item purchase given a primary anchor item.
- **Lift:** Isolated strong, actionable cross-selling opportunities where the rule strength outpaces baseline independent item popularity.

## 💻 Tech Stack Used
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebooks
- **Libraries:** Pandas, NumPy (Data handling), Mlxtend (Machine Learning / Apriori), Matplotlib, Seaborn (Data visualization)
