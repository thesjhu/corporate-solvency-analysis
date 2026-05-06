# Corporate Solvency & Financial Health Analytics

### **Project Overview**
This project implements the **Altman Z-Score Model** to programmatically assess the bankruptcy risk of publicly traded companies. By integrating real-time financial statement data with quantitative risk formulas, the analysis categorizes firms into "Safe," "Grey," or "Distress" zones.

As a bridge between financial reporting and data analytics, this tool automates the extraction of Balance Sheet and Income Statement metrics to provide a snapshot of corporate stability.

### **Analytical Methodology**
The Altman Z-Score is a multivariate statistical formula used to predict the probability that a firm will go into bankruptcy within two years. The model utilizes five key financial ratios:

*   **Liquidity:** Working Capital / Total Assets
*   **Cumulative Profitability:** Retained Earnings / Total Assets
*   **Operating Efficiency:** EBIT / Total Assets
*   **Solvency:** Market Capitalization / Total Liabilities
*   **Asset Turnover:** Sales / Total Assets

### **Technical Features**
*   **Automated Data Pipeline:** Fetches live financial data (Total Assets, EBIT, Retained Earnings, etc.) via the `yfinance` API.
*   **Custom Risk Mapping:** Implements conditional logic to visualize financial standing through color-coded distribution charts.
*   **Comparative Benchmarking:** Evaluates multiple tickers simultaneously to compare industry leaders against distressed entities.
*   **Data Visualization:** Utilizes Seaborn and Matplotlib to create executive-level dashboards with clear risk thresholds.

---

### **Technical Stack**
*   **Language:** Python 3.x
*   **Libraries:** Pandas, NumPy, Seaborn, Matplotlib
*   **API:** Yahoo Finance (yfinance)

---

### **Installation & Usage**

**1. Clone the repository**
```bash
git clone https://github.com/thesjhu/corporate-solvency-analytics.git
cd corporate-solvency-analytics
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn yfinance
```

**3. Execution**
Run the Jupyter Notebook `corporate_solvency_analysis.ipynb` to view the analysis. You can modify the `tickers` list in the second cell to analyze any publicly traded company.

---

### **Key Insights**
*   Successfully identified the divergence in solvency between high-growth tech firms and capital-intensive industries.
*   Demonstrated how market capitalization volatility (Variable D) can drastically shift a company's risk profile even when operational metrics remain stable.

---

### **Author**
**Sijie Hu**  
MS in Information Systems, Data Analytics | Baruch College
