# Hi there! I'm Pavan Kumar 👋

<p align="center">
  <a href="https://www.linkedin.com/in/pavankumar-m/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:pavankumar@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/pavankumarM1998"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

### 🚀 Data Engineer & BI Specialist

I am a passionate **Data Engineer** and **BI Specialist** dedicated to building high-performance, automated data pipelines (ETL/ELT), modeling clean data warehouses, and building interactive enterprise dashboards. I specialize in the Microsoft and Azure data stack (Azure Data Factory, Azure SQL, Power BI) along with scripting languages like SQL and Python to convert complex raw data into business intelligence.

> 💡 *"Data is the new oil, but ETL is the refinery — and I design the pipelines that keep it running."*

---

## 🛠️ Tech Stack & Expertise

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>💾 Databases & Storage</h3>
      <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white" alt="SQL Server" />
      <img src="https://img.shields.io/badge/Azure%20SQL%20Database-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white" alt="Azure SQL" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
    </td>
    <td valign="top" width="50%">
      <h3>⚙️ ETL & Data Engineering</h3>
      <img src="https://img.shields.io/badge/Azure%20Data%20Factory-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white" alt="ADF" />
      <img src="https://img.shields.io/badge/SSIS-CC2927?style=flat-square&logo=microsoft&logoColor=white" alt="SSIS" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/Databricks-FF6F00?style=flat-square&logo=databricks&logoColor=white" alt="Databricks" />
      <img src="https://img.shields.io/badge/Delta%20Lake-0089D6?style=flat-square&logo=linux&logoColor=white" alt="Delta Lake" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>📊 Business Intelligence & Reporting</h3>
      <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI" />
      <img src="https://img.shields.io/badge/DAX-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="DAX" />
      <img src="https://img.shields.io/badge/SSRS-CC2927?style=flat-square&logo=microsoft&logoColor=white" alt="SSRS" />
      <img src="https://img.shields.io/badge/MS%20Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Excel" />
    </td>
    <td valign="top" width="50%">
      <h3>☁️ Cloud & Infrastructure</h3>
      <img src="https://img.shields.io/badge/Microsoft%20Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white" alt="Azure" />
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS" />
      <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white" alt="GCP" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
    </td>
  </tr>
</table>

---

## 🚀 Highlighted Projects

### 🚗 [Veyro: End-to-End Real-Time Stream-to-Report Pipeline](https://github.com/pavankumarM1998/Veyro)
A production-grade, end-to-end real-time streaming data platform and interactive analytics dashboard:
*   **Real-Time Event Simulator**: FastAPI application generating live booking events, calculating dynamic fares, and surge rates.
*   **Streaming Ingestion**: Asynchronous event streaming to Azure Event Hubs namespace using the Python SDK.
*   **Databricks Medallion Architecture**: Spark Structured Streaming refining raw events (Bronze) into validated/watermarked records (Silver) and joining with lookup dimensions to produce a denormalized One Big Table (OBT) Delta Lake table (Gold).
*   **Agentic Power BI Development**: 4-tab dashboard and semantic model built programmatically (.pbip format) using advanced developer skills.
*   **Live DirectQuery Insights**: Interactive reports connected via Databricks SQL Warehouse to serve live updates with zero data latency.
👉 **[Live Veyro Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiYmY2MmVmNGEtNDY0NC00MWQxLWJkOTctYzY5MzhjNTJhNTBlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

### 🌩️ [Advanced ADF Data Pipelines](https://github.com/pavankumarM1998/ADF-Project)
Production-grade Azure Data Factory repository showcasing enterprise-ready integration patterns:
*   **Watermark-Based CDC:** Incremental ingestion pipeline storing states in ADLS Gen2 checkpoints (`cdc.json`).
*   **Switch-Based Routing:** Metadata-driven directory file router separating files to targets based on prefix evaluations.
*   **Dynamic Translation Maps:** Automatic schema-mapped ingestion matching runtime files dynamically to configuration parameters.
*   **Web API Pagination:** Custom pagination rules using JSON-based offset counts fetched dynamically from active endpoints.
*   **Mapping Data Flows:** Clean ETL transformations using Spark computation to output optimized Snappy-Parquet and Delta Lake formats.

### 🛠️ [ADF Learning & Orchestration](https://github.com/pavankumarM1998/ADF-Learning-projects)
Operational repository highlighting intermediate control-flow patterns:
*   **Sequential Loop Orchestration:** Wrappers coordinating file verification activities before sequential loop executions.
*   **Auto-Cleanup & Ingest:** Cut-and-paste file archival runs deleting processed files to optimize cloud storage size.
*   **GitHub Server Integration:** Direct raw Git downloads pulling datasets automatically into lake storage.
*   **Variable State Logging:** Demonstration of array variables capturing runtime system variables.

### 📈 [AtliQ Business 360 Dashboard](https://github.com/pavankumarM1998)
A unified Power BI analytics dashboard covering Sales, Finance, and Supply Chain reporting:
*   Ingested **1M+ rows** of multi-source MySQL/Excel data.
*   Optimized data schemas using **DAX Studio** to gain **30% storage savings** and **10% faster load rates**.
*   Built dynamic metrics to analyze profitability, net sales, and market share trends.

---

## 📊 GitHub Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pavankumarM1998&show_icons=true&theme=nord&border_radius=10" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pavankumarM1998&layout=compact&theme=nord&border_radius=10" alt="Top Langs" width="48%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=pavankumarM1998&theme=nord" alt="Streak Stats" width="98%" />
</p>

---

<p align="center">
  <i>Building robust pipelines and turning data into answers, one workflow at a time.</i> 🚀
</p>
