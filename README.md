<div align="center">
  <img src="https://raw.githubusercontent.com/Bharath-Naveen/Bharath-Naveen/main/github-header.png" alt="Bharath Naveen — Data Scientist, ML Engineer, Data Analyst, Forward Deployed Engineer" width="100%">
</div>

<p align="center">
  <a href="https://bharathnaveen.com"><img src="https://img.shields.io/badge/Portfolio-bharathnaveen.com-0E7C86?style=flat&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/bharath-naveen/"><img src="https://img.shields.io/badge/LinkedIn-0E7C86?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="mailto:bharathnaveen.bn@gmail.com"><img src="https://img.shields.io/badge/Email-0E7C86?style=flat&logo=gmail&logoColor=white"></a>
</p>

## About

I build end-to-end data and machine learning systems, from database design and ETL pipelines to modeling, evaluation, and production deployment. I came to data through mechanical engineering and 3+ years of enterprise analytics at Tata Consultancy Services, so I care as much about clean pipelines, data validation, and clear communication as I do about the model itself. I hold an MS in Information Science (Machine Learning) from the University of Arizona, and I'm open to **Data Scientist, Machine Learning Engineer, Data Analyst, and Forward Deployed Engineer** roles.

Plain-language writeups of every project below live on my portfolio: **[bharathnaveen.com](https://bharathnaveen.com)**.

![Python](https://img.shields.io/badge/Python-0E7C86?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-0E7C86?style=flat&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-0E7C86?style=flat&logo=r&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-0E7C86?style=flat&logo=julia&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-0E7C86?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0E7C86?style=flat&logo=docker&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0E7C86?style=flat&logo=scikitlearn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-0E7C86?style=flat&logo=powerbi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-0E7C86?style=flat&logo=streamlit&logoColor=white)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bharath-Naveen&layout=compact&langs_count=8&hide_border=true&title_color=2DC6C0&text_color=C4CDD7&bg_color=0C1620" alt="Most used languages" />
</div>

---

## Featured work

Each project leads with the problem it solves and the skills behind it. Repo links are inline; deeper writeups are on [bharathnaveen.com](https://bharathnaveen.com).

**[Phishing Detection System](https://github.com/Bharath-Naveen/containerized-phishing-project)**<br>
**Problem:** Phishing sites appear and vanish faster than blocklists can react, and naive URL models over-flag legitimate, modern JavaScript-heavy pages.<br>
**Built:** Engineered a layered detection system, supervised ML triage (LightGBM, XGBoost, Random Forest, Logistic Regression) over 500K+ URL and host features, live page capture with Playwright, HTML/DOM behavior analysis, and a deterministic evidence-adjudication layer that returns explainable safe / suspicious / phishing verdicts. Containerized with Docker, deployed on AWS, and surfaced through a Streamlit dashboard.<br>
**Skills:** `Python` `LightGBM` `XGBoost` `Feature engineering` `Applied NLP` `Model evaluation` `Playwright` `Docker` `AWS` `Streamlit`<br>
**Role fit:** Data Scientist · ML Engineer · Forward Deployed Engineer

**[Cohort Analytics Platform](https://github.com/Bharath-Naveen/cohort-analytics)**<br>
**Problem:** University advisors had no fast way to see whether student cohorts were on track, behind, or ahead of their degree pace.<br>
**Built:** Designed and built the serverless data and ETL layer end to end, a containerized Julia ETL on AWS ECS/Fargate, degree-progress classification logic, DynamoDB with query-tuned indexes, a Lambda API, and multi-environment CI/CD, working directly with university stakeholders to ship it into production.<br>
**Skills:** `AWS Lambda` `DynamoDB` `ECS/ECR` `ETL pipeline design` `Data modeling` `CI/CD` `Julia` `Stakeholder delivery`<br>
**Role fit:** Data Analyst · ML Engineer · Forward Deployed Engineer

**[YouTube Comment Spam Detector](https://github.com/Bharath-Naveen/youtube-comment-spam-detector)**<br>
**Problem:** Harmful comments (phishing scams, bait bots, engagement spam) erode trust and distort engagement metrics, with no labeled dataset to learn from.<br>
**Built:** Built an end-to-end NLP classification pipeline, collected data via the YouTube Data API, generated labels with rule-based weak supervision plus manual validation, engineered behavioral features (link density, emoji frequency, repetition), and trained a TF-IDF + logistic-regression multi-class model tuned for high precision on the highest-risk categories.<br>
**Skills:** `Python` `Applied NLP` `TF-IDF` `scikit-learn` `Feature engineering` `Weak supervision` `Model evaluation` `API integration`<br>
**Role fit:** Data Scientist · ML Engineer

**[AutoRisk](https://github.com/Bharath-Naveen/AutoRisk)** *(in progress)*<br>
**Problem:** First-time student buyers on a $5–10k budget can't easily judge which cheap used car is a reliable, safe bet.<br>
**Built:** Building a data product that ingests NHTSA complaints, recalls, and investigations, clusters failure patterns with TF-IDF and KMeans, models depreciation with XGBoost, and combines them into a composite reliability score served through a Streamlit app. Modular and Docker-ready.<br>
**Skills:** `Python` `XGBoost` `Applied NLP` `Clustering` `API ingestion` `Streamlit` `Docker`<br>
**Role fit:** Data Scientist · ML Engineer · Forward Deployed Engineer

## More projects

**[BN Motors — SQL Data System](https://github.com/Bharath-Naveen/bn_motors_SQL)**<br>
**Problem:** A multi-store dealership's sales, service, financing, and parts data was siloed, with no reliable way to report on it.<br>
**Built:** Designed a normalized 26-table relational database from the ER model up (MySQL 8), and wrote advanced analytical SQL (joins, window functions, CTEs, subqueries) plus reusable reporting views for inventory aging, gross-profit attribution, finance penetration, lead-to-sale funnels, and customer lifetime value.<br>
**Skills:** `MySQL` `SQL` `ER modeling` `Schema design` `Window functions` `CTEs` `Business reporting`<br>
**Role fit:** Data Analyst · Data Scientist

**[Loan Default Prediction](https://github.com/Bharath-Naveen/german-loan-default-ml-)**<br>
**Problem:** Lenders need to flag likely defaulters early, on imbalanced credit data where accuracy alone is misleading.<br>
**Built:** Ran a full supervised-learning workflow, EDA, preprocessing, and feature engineering on economic variables, then benchmarked five models (Logistic Regression, Decision Tree, Random Forest, SVM, Gradient Boosting) tuned for recall and F1, and surfaced the real risk drivers (low balances, short tenure, thin credit history).<br>
**Skills:** `Python` `scikit-learn` `Gradient Boosting` `Random Forest` `SVM` `Feature engineering` `EDA` `Imbalanced data` `Model evaluation`<br>
**Role fit:** Data Scientist · Data Analyst

**[YouTube Analytics Pipeline](https://github.com/Bharath-Naveen/youtube-analytics-pipeline)**<br>
**Problem:** Manually gathering YouTube performance data doesn't scale for trend and sentiment analysis.<br>
**Built:** Built an automated pipeline that extracts video and comment data via the YouTube Data API, structures views, likes, and comment text, stores it as JSON, and enables engagement-trend and sentiment analysis with Plotly visualizations.<br>
**Skills:** `Python` `YouTube Data API` `ETL` `Data cleaning` `EDA` `Plotly`<br>
**Role fit:** Data Analyst

**[TMDB Movie Scraper](https://github.com/Bharath-Naveen/tmdb-movie-scraper)**<br>
**Problem:** Structured movie and review data isn't readily available for downstream analytics.<br>
**Built:** Built a web-scraping pipeline that extracts, cleans, and exports structured movie and review datasets ready for analysis.<br>
**Skills:** `Python` `BeautifulSoup` `Web scraping` `Data cleaning` `ETL`<br>
**Role fit:** Data Analyst

---

## What I work with

| Area | Tools |
| --- | --- |
| **Languages & querying** | Python (pandas, NumPy, scikit-learn), SQL (CTEs, window functions, stored procedures), R, Julia |
| **BI & reporting** | Power BI, DAX, Streamlit, Plotly — dashboards built for non-technical stakeholders |
| **Data engineering** | AWS (Lambda, DynamoDB, S3, ECS/ECR), ETL pipeline design, data validation, ER modeling |
| **Machine learning** | scikit-learn, XGBoost, LightGBM, applied NLP, exploratory data analysis, model evaluation |

---

## Experience

**Systems Engineer, Data & Analytics — Tata Consultancy Services** · 3+ years<br>
Built the Power BI dashboards, SQL, and Python reporting automation that Microsoft-account stakeholders made release decisions from, automated reporting pipelines that cut days of manual work per cycle, and ran exploratory analysis across hundreds of test and defect records, with a focus on data validation and cross-team communication. The enterprise-scale foundation behind everything above.

---

## Open to

`Data Scientist` · `Machine Learning Engineer` · `Data Analyst` · `Forward Deployed Engineer`

<p align="center">
  <a href="https://bharathnaveen.com">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/bharath-naveen/">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:bharathnaveen.bn@gmail.com">Email</a>
</p>
