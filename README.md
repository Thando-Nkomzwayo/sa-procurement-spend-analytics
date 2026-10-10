# South African Municipal Procurement Spend & Compliance Analytics

## 📋 Business Problem
Public sector and municipal procurement in South Africa must strictly adhere to regulatory frameworks like the Municipal Finance Management Act (MFMA) and Public Finance Management Act (PFMA). A major vulnerability in municipal supply chains is **split-tendering**—where large orders are artificially broken down into smaller tranches just beneath mandatory competitive tender thresholds (e.g., the R200,000 audit limit) to bypass stringent governance checks. 

This project builds an automated Python data pipeline to ingest procurement logs, audit transaction values against regulatory thresholds, identify supplier concentration risk, and visualize spending anomalies.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Analysis:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Google Colab

---

## 📊 Key Features & Analysis
1. **Automated Compliance Auditing:** Flags purchase orders falling into high-risk bands near critical audit thresholds (e.g., between R180,000 and R200,000).
2. **Supplier Concentration Metrics:** Aggregates total spend and order volume per supplier to highlight vendor dependency.
3. **Exploratory Visualizations:** Generates distribution plots and comparative spend barcharts to support internal audit and procurement governance teams.

---

## 🚀 How to Run the Code
1. Clone this repository or download the `procurement_analysis.py` script.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
