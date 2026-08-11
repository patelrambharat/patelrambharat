<h1 align="center">Hi 👋, I'm Rambharat Patel</h1>
<h3 align="center">Data Engineer | Azure • PySpark • Databricks | Big Data & Cloud Enthusiast</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=650&lines=Azure+Data+Factory+%7C+Databricks+%7C+PySpark;Building+Scalable+ETL+%26+Data+Pipelines;4.6%2B+Years+in+Big+Data+Engineering;Medallion+Architecture+%7C+Delta+Lake+%7C+Snowflake" alt="Typing SVG" />
</p>

---

### 👤 About Me

- 🔭 Currently working at **Accenture Solutions Pvt. Ltd.** as a **Data Engineer**
- 💼 4.6+ years of experience in **API Integration, Data Quality, Data Streaming, and PII Data handling**
- ☁️ Skilled in migrating on-premise files to **Azure Storage (Raw → Refine → Snowflake Layer)**
- 🧠 Proficient in **PySpark, Databricks, Python, SQL, and Azure Data Factory**
- 🌱 Strong understanding of **distributed computing principles** and Medallion Architecture
- 💬 Ask me about **ETL pipelines, Azure Databricks, ADF, Delta Lake, Data Warehousing**
- 📫 Reach me at **patelrambharat@gmail.com**

---

### 🔗 Connect with me

<p align="left">
<a href="https://www.linkedin.com/in/rambharat-patel-5a208a14b/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" height="30" width="40" /></a>
<a href="https://www.codechef.com/users/bharat22" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.1.0/icons/codechef.svg" height="30" width="40" /></a>
<a href="https://codeforces.com/profile/bharat22" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/codeforces.svg" height="30" width="40" /></a>
<a href="https://leetcode.com/pbharatpatel/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" height="30" width="40" /></a>
<a href="mailto:patelrambharat@gmail.com" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/gmail.svg" height="30" width="40" /></a>
</p>

---

### 🛠️ Tech Stack

<p align="left">
<img src="https://skillicons.dev/icons?i=python,azure,java,git,github,jenkins" />
</p>

**Languages:** Python • SQL • Scala (Spark) • JSON • YAML
**Big Data & Cloud:** ![Databricks](https://img.shields.io/badge/-Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white) ![Spark](https://img.shields.io/badge/-Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) Azure Synapse Analytics • ADLS Gen2 • Delta Lake
**Platforms:** Microsoft Azure
**ETL Tools:** Azure Data Factory (ADF) • Azure Functions • SSIS
**Database & Storage:** SQL Server / Azure SQL • Oracle • HDFS • DBeaver
**DevOps & CI/CD:** GitHub/Bitbucket • Jenkins • Jira • Control-M
**Soft Skills:** Team Leadership • Project Management • Agile & Scrum

---

### 🏢 Career Timeline

```mermaid
timeline
    title Accenture Solutions Pvt. Ltd. — Career Progression
    Jan 2022 - May 2024 : Data Engineer — Project BSC (Celerity)
                        : ADF pipelines, watermark ingestion, Bronze/Silver/Gold layers
    TBD                 : Data Engineer — Project Enhancement (MDF)
                        : Medallion Architecture, PySpark/SQL transformations
    TBD                 : Data Engineer — Project HSSC (Clarity)
                        : Shell scripting, Control-M, ADLS Gen2 ingestion
    May 2024 - Present  : Data Engineer — Project ACFC (Azure Framework)
                        : End-to-end ADF pipelines, PII masking, client demos
```
> ⚠️ Two role dates are still marked **TBD** — same placeholders flagged in your resume. Fill these in before publishing so the timeline lines up correctly (currently listed in resume order, not confirmed chronological order).

<details>
<summary><b>📌 Role details (click to expand)</b></summary>

**Data Engineer | Project: ACFC – Azure Framework** *(May 2024 – Present)*
- Developed end-to-end data pipelines using **ADF** to orchestrate movement of structured/unstructured data from SQL Server, Oracle, APIs, and Azure Blob Storage
- Optimized **PySpark notebooks in Azure Databricks** for batch and streaming transformations
- Performed **schema drift management** using dynamic dataflows in ADF
- Used **Azure Key Vault** to manage credentials, SAS tokens, and connection strings
- Built parameterized ADF pipelines (Lookup, ForEach, If Condition) for dynamic ETL
- Conducted **client demos** and translated business requirements into scalable solutions
- Implemented **PII data masking and encryption** using PySpark transformations

**Data Engineer | Project: HSSC – Clarity**
- Worked on on-premise source data using **shell scripting and Control-M**
- Pre-processed raw data on **Databricks using PySpark**
- Implemented **ADLS Gen2** workflows for raw ingestion, refinement, and downstream processing
- Deployed code via **Jenkins and UCD** after unit testing

**Data Engineer | Project: BSC – Celerity** *(Jan 2022 – May 2024)*
- Designed **ADF pipelines** for ingestion from on-premises, SQL Server, APIs, and cloud sources into ADLS Gen2
- Implemented **incremental/watermark-based ingestion** to avoid reprocessing records
- Configured **Self-Hosted Integration Runtime** for secure on-prem-to-Azure connectivity
- Designed **Bronze, Silver, Gold** data layers in ADLS Gen2
- Participated in **Agile ceremonies** (sprint planning, stand-ups, retrospectives)

**Data Engineer | Project: Enhancement – MDF**
- Designed end-to-end Azure solution using **Medallion Architecture**
- Built transformation workflows using **Databricks, Apache Spark, PySpark, SQL**
- Performed **source-to-target validation** for data accuracy and completeness
- Designed and executed **test plans and test cases** for Big Data applications

</details>

---

### 🔄 Data Pipeline Architecture (Medallion Pattern)

```mermaid
graph LR
    A[On-Prem SQL Server / Oracle / APIs] -->|ADF Ingestion| B[Bronze Layer<br/>Raw Data - ADLS Gen2]
    B -->|PySpark: Dedup, Filter, Clean| C[Silver Layer<br/>Refined Data]
    C -->|Aggregation, Enrichment| D[Gold Layer<br/>Business-Ready Data]
    D --> E[Snowflake / Analytics & Reporting]

    F[Azure Key Vault] -.Secrets & Credentials.-> B
    G[Databricks + PySpark] -.Transformations.-> C
    H[Self-Hosted Integration Runtime] -.Secure Connectivity.-> A

    style B fill:#CD7F32,color:#fff
    style C fill:#C0C0C0,color:#000
    style D fill:#FFD700,color:#000
    style E fill:#2E9EF7,color:#fff
```

---

### 🚀 Key Achievements

| Achievement | Detail |
|---|---|
| 🏅 Checksum-based deduplication framework | Built in PySpark + ADF, ensured 100% data accuracy |
| 🏆 Microsoft Certified: Azure Data Engineer Associate | DP-203 |
| 🥇 Top performer | Recognized in quarterly reviews for on-time delivery |

---

### 🎓 Education

**Bachelor of Technology in Electronics and Communication Engineering**
*Madan Mohan Malaviya University of Technology | July 2018 – July 2021*
CGPA: 8.31 / 10.0

---

### 📜 Certifications

| Certification | Issuer |
|---|---|
| ✅ Microsoft Certified: Azure Data Engineer Associate (DP-203) | Microsoft |
| ✅ Semiconductor Optoelectronics | NPTEL |

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=patelrambharat&show_icons=true&theme=tokyonight" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=patelrambharat&layout=compact&theme=tokyonight" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=patelrambharat&theme=tokyonight"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=patelrambharat&color=blueviolet&style=flat-square" alt="Profile views" />
</p>
