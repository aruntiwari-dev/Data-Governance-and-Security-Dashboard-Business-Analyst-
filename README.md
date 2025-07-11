# Data-Governance-and-Security-Dashboard-Business-Analyst-

This project demonstrates how to build a comprehensive and interactive Data Governance and ESG Security Dashboard using **Tableau**, **SQL**, and **Excel**. It covers key metrics like data quality, privacy, access, security incidents, and ESG performance across countries using World Bank ESG data.

---

##  Tools & Technologies

- 📈 **Tableau Desktop** – for interactive dashboards and visual analytics  
- 🗃️ **SQL** – for data preparation and transformation  
- 📊 **Microsoft Excel** – for cleaning and structuring raw ESG data

---

##  Dataset

The project uses the **World Bank’s ESG Data Draft** dataset. It includes 17 sustainability indicators across three domains:

- 🌱 Environment  
- 🧑‍🤝‍🧑 Social  
- 🏛️ Governance  

 Dataset Download:  
[🔗 Google Drive Folder](https://drive.google.com/drive/folders/1UPMO5PMiJvBbLzpRhuHjCtf5o3_lN3fD?usp=sharing)

---

##  Objectives

- Visualize ESG indicators by country.
- Monitor data access, privacy, compliance, and security metrics.
- Enable decision-makers to identify trends, breaches, and compliance gaps.
- Deliver insights in a user-friendly Tableau dashboard.

---

##  Dashboard Features

### ✅ ESG Indicators Dashboard
- **World Map** showing ESG values by country
- **Bar Chart** comparing selected indicators across nations
- **Tooltip Panel** with full Series Code descriptions
- **Filters** for ESG Category (E/S/G), Series Code, and Country

### ✅ Data Governance Dashboard
1. **Data Quality**
   - Line chart for Accuracy, Completeness, Consistency
   - Calculated Fields:
     - `Accuracy Rate = SUM(AccurateRecords)/SUM(TotalRecords)`
     - `Completeness Rate = SUM(CompleteRecords)/SUM(TotalRecords)`

2. **Data Access**
   - Bar chart & heatmap for access requests, approvals, and departments
   - Calculated Fields:
     - `Approved Requests = COUNT(IF RequestStatus = 'Approved')`
     - `Avg Approval Time = AVG(DATEDIFF('day', RequestDate, ApprovalDate))`

3. **Data Privacy**
   - Pie chart of compliance status
   - Line chart for access trends
   - `Privacy Compliance Rate = Compliant Accesses / Total Accesses`

4. **Data Security**
   - Scatter plot of incident types vs detection time
   - Bar chart for unauthorized access attempts

5. **Compliance**
   - Line chart for audit status
   - `Compliance Rate = Passed Audits / Total Audits`

---

##  Key Insights (Sample Report)

| Metric                                | Value            |
|--------------------------------------|------------------|
| ✅ Data Accuracy Rate                | 98%              |
| 🔒 Unauthorized Access Attempts      | 5                |
| 📑 Compliance Rate                   | 95%              |
| 📉 Trend: Data Quality ↑             | +2% in Q4        |
| 📬 Access Requests (Total)           | 150              |
| 📬 Approved Requests                 | 140              |
| ⏱️ Avg Approval Time                | 2 days           |
| 🔐 Privacy Compliance                | 98%              |
| ⚠️ Security Incidents                | 3                |
| ⏱️ Avg Incident Response Time       | 30 minutes       |

---

##  How to Use

1. Download the dataset and open **Tableau Desktop**  
2. Connect all data sources (Excel or CSV files)  
3. Create calculated fields as per documentation  
4. Build individual sheets for:
   - Data Quality
   - Data Privacy
   - Data Access
   - Security & Compliance  
5. Combine sheets into an interactive dashboard
6. Export as PDF/image or publish to **Tableau Public/Server**

---

##  Deliverables

- ✅ Tableau `.twbx` workbook  
- ✅ Excel/CSV data sources  
- ✅ Final PDF dashboard (optional export)  
- ✅ Summary report of key metrics

---

## Reference

This project is inspired by:
[Tableau Dashboard Repository – Covid Analysis](https://github.com/hiranvjoseph/Tableau-Dashboard-Repository/tree/main/Covid_Data_Analysis)

---

##  Contact

**Author**: Arun Tiwari  
📧 Email: aruntiwari1639@gmail.com 

---

##  License

MIT License – Feel free to use or adapt this project for learning and academic purposes.
