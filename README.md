# 📊 IBM Data Analyst Capstone Project  
**Author:** Valentina Loayza  
**Course:** IBM Data Analyst Professional Certificate  

---

## 🧩 Project Overview
This project presents an in-depth analysis of the **global developer landscape** based on the Stack Overflow Developer Survey.  
It explores **programming languages, databases, and developer demographics** to identify major industry trends and emerging technologies shaping the modern software ecosystem.

The study combines **Python-based data wrangling and visualization** with **executive dashboards built in IBM Cognos Analytics**, offering both analytical depth and business insight.

---

## 🧠 Objectives
- Identify the **most used and desired programming languages** among developers.
- Examine trends in **database technologies** and the shift toward open-source solutions.
- Analyze the **demographic and educational profile** of global developers.
- Visualize these insights through interactive **IBM Cognos dashboards** and Python-based visualizations.

---

## ⚙️ Tools & Technologies
- **Python:** Pandas, Matplotlib  
- **IBM Cognos Analytics:** Dashboard design and data visualization  
- **Jupyter Notebook:** Data wrangling and exploration  
- **Dataset:** Stack Overflow Developer Survey (via IBM Skills Network)

---

## 🔍 Methodology
1. **Data Preparation**  
   - Cleaned raw CSV data and removed missing values.  
   - Split multi-select survey fields (e.g., `LanguageHaveWorkedWith`) for frequency analysis.  

2. **Analysis & Visualization**  
   - Aggregated results to find top technologies, languages, and databases.  
   - Created visualizations in Python (Matplotlib) and IBM Cognos.  

3. **Insights & Reporting**  
   - Summarized key patterns and implications for developers and hiring managers.  
   - Delivered results through dashboards and a professional presentation.

---

## 📈 Dashboards
**IBM Cognos Dashboard (Interactive View):**  
🔗 [Click here to open the dashboard](https://us3.ca.analytics.ibm.com/bi/?perspective=dashboard&pathRef=.my_folders%2Fcapstone&action=view&mode=dashboard&subView=model00000199a6376cc3_00000006)

**Dashboard Preview:**  
![Cognos Dashboard](dashboards/cognos-dashboard.png)

---

## 💡 Key Insights
- **JavaScript** and **Python** dominate as core development languages, while **Go** and **Rust** show remarkable growth in interest.  
- **PostgreSQL** and **MySQL** remain the most valuable database skills, reflecting the rise of open-source technologies.  
- The **developer community is predominantly young and university-educated**, concentrated in tech hubs such as the **U.S., India, and Western Europe**.  
- **Cloud-native development** has become the norm, with **Docker** and **AWS** among the most essential technologies.  

---

## 🧾 Results Summary
| Category | Current Leaders | Emerging Trends |
|-----------|----------------|----------------|
| Programming Languages | JavaScript, Python, HTML/CSS, SQL | Go, Rust, TypeScript |
| Databases | MySQL, PostgreSQL | MongoDB, Redis |
| Platforms | Linux, Windows | Docker, AWS |
| Workforce | Ages 25–34, University-educated | Expanding globally, tech hubs in US & India |

---

## 🗂️ Repository Structure
```bash
📁 ibm-data-analyst-capstone/
│
├── 📄 README.md
├── 📁 data/
│   └── dataset.csv
│
├── 📁 notebooks/
│   ├── wrangling.ipynb
│   └── analysis.ipynb
│
├── 📁 dashboards/
│   ├── cognos-dashboard.png
│   └── cognos-dashboard-link.txt
│
├── 📁 presentation/
│   └── DataAnalystPresentation.pdf
│
└── 📁 visuals/
    ├── languages_trend.png
    ├── databases_trend.png
    ├── demographics.png
    └── job_postings.png
