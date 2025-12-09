# 🏦 BanVic Challenge – Data Analysis / Analytics Engineering  
### Indicium Lighthouse – Assessment Case  
**Author:** Felipe Rocha Casco  
📧 feliperochacasco@yahoo.com.br  

---

## 📌 About the Project
This repository contains the full development of the **BanVic Challenge**, completed for **Indicium Lighthouse**, focused on **Data Analysis, Analytics Engineering, and Business Intelligence**.

The objective of this study was to perform an exploratory, behavioral, and temporal analysis of BanVic customers, transactions, proposals, and financing operations in order to identify strategic patterns to support decision-making.

---

# 📊 1. Exploratory Data Analysis — Key Metrics

| Indicator | Result |
|----------|--------|
| **Total Proposal Volume** | **R$ 167.78 million** |
| **Average Installment Value** | **R$ 4.88 thousand** |
| **Total Financed Volume** | **R$ 249.52 million** |
| **Average Down Payment** | **R$ 40.87 thousand** |
| **Average Approved Transactions (Year/Quarter)** | **2.5 thousand** |
| **Customer Profile** | Mostly **61+ years old**, located in **AM, ES, SP, MS** |

---

# 📈 2. Insights and Quantitative Indicators
The analysis uncovered important behavioral and financial patterns:

### 🔹 Customer Profile
- Majority of clients are seniors (61+)  
- High concentration in the states: AM, ES, SP, MS  

### 🔹 Behavioral Trends
- Significant volumes in proposals and financing  
- Clear seasonal demand patterns  

These findings support targeted marketing actions, credit strategies, and customized service offerings.

---

# 📆 3. Temporal Analysis – Dim Calendar

| Metric | Insight |
|--------|--------|
| **Quarter with the Most Approved Transactions** | Q3 |
| **Quarter with the Highest Financial Volume** | Q4 |
| **Month with the Highest Transaction Volume** | December |
| **Month with the Lowest Volume** | April |
| **Seasonal Peaks** | July, October, November, December |

🔍 *Validation:* months containing “R” do **not** present statistically significant differences.

---

# 🌐 4. Public Data Sources Used
To enrich the analysis, external datasets were incorporated:

### 📌 Economic Indicators  
- **IPCA (2020–2025)**  
- Overall correlation with transaction volume: **low**, but relevant for trend monitoring  

### 📌 Population Data (IBGE)  
Used to understand:  
- Client demographic distribution  
- Potential market expansion by state  

---

# 🔧 5. Data Transformation & Engineering Processes

The following processes were applied:

- ✔ **Encoding correction**  
- ✔ **Date standardization**  
- ✔ Category cleanup and normalization  
- ✔ Creation of **age** and **age group** fields  
- ✔ **Outlier removal**  
- ✔ Table merging with **Dim Calendar**  
- ✔ Data modeling using Power Query (M) and DAX  

---

# 🧠 6. Insights for Decision-Making
Strategic insights extracted from the analysis:

### 📌 Most profitable quarters  
— Key periods for marketing and credit strategies.

### 📌 Seasonal transaction peaks  
— Ideal for product launches and promotional campaigns.

### 📌 Customer segmentation  
— Senior customers represent the strongest opportunity for tailored financial products.

---

# 📝 7. Recommendations for BanVic’s CEO

### 🎯 Seasonal Strategy Optimization  
Leverage high-performing months for targeted promotions and revenue maximization.

### 👴 Customer Segmentation  
Develop products aimed at seniors, the dominant demographic in the dataset.

### 📊 Economic Scenario Monitoring  
Expand macroeconomic correlation studies beyond IPCA.

### 🛠 Data Quality Enhancement  
Implement automated pipelines for:  
- validation  
- standardization  
- consistency checks  

---

# 🧰 8. Tools & Technologies

Tool | Purpose
---- | --------
**Excel** | Initial exploration and validation  
**Power BI** | Interactive data visualization and dashboarding  
**Power Query (M)** | Data transformation and modeling  
**DAX** | Metric creation and analytical calculations  
**Python/Notebooks** | Optional EDA and validation  

---

# 📁 Files Included

- **CSV:** agencias, clientes, colaborador_agencia, colaboradores, contas, propostas_credito, transacoes  
- **XLS:** IPCA 2020–2025  
- **Power BI:** `LH_BANVIC_FELIPECASCO.pbix`  
- **Presentation:** `LH_EA_felipeRochaCasco.pdf`  

---

# 📂 Repository Structure
For a full overview of the repository layout, refer to the structure listed in the root of this project.

---

# 📜 License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

# 👤 Author
**Felipe Rocha Casco**  
📧 Contact: **feliperochacasco@yahoo.com.br**

