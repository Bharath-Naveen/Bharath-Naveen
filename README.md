<div align="center">
  <img src="https://raw.githubusercontent.com/Bharath-Naveen/Bharath-Naveen/main/github-header-anim.gif" alt="Bharath Naveen — Data Scientist, ML Engineer, Data Analyst, Forward Deployed Engineer" width="100%">
</div>

<p align="center">
  <a href="https://bharathnaveen.com"><img src="https://img.shields.io/badge/Portfolio-bharathnaveen.com-0E7C86?style=flat&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/bharath-naveen/"><img src="https://img.shields.io/badge/LinkedIn-0E7C86?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="mailto:bharathnaveen.bn@gmail.com"><img src="https://img.shields.io/badge/Email-0E7C86?style=flat&logo=gmail&logoColor=white"></a>
</p>

## About

I build **end-to-end data and machine learning systems**, from database design and ETL pipelines to modeling, evaluation, and production deployment. I came to data through mechanical engineering and **3+ years of enterprise analytics at Tata Consultancy Services**, so I care as much about clean pipelines, data validation, and clear communication as I do about the model itself. I hold an **MS in Information Science (Machine Learning)** from the University of Arizona, and I'm open to **Data Scientist, Machine Learning Engineer, Data Analyst, and Forward Deployed Engineer** roles.

Plain-language writeups of every project below live on my portfolio: **[bharathnaveen.com](https://bharathnaveen.com)**.

| Core stack | |
| --- | --- |
| **Languages** | Python (pandas, NumPy, scikit-learn), SQL (CTEs, window functions, stored procedures), R, Julia |
| **ML & modeling** | scikit-learn, XGBoost, LightGBM, applied NLP, exploratory data analysis, model evaluation |
| **Data & cloud** | AWS (Lambda, DynamoDB, S3, ECS/ECR), ETL pipeline design, data validation, ER modeling |
| **BI & delivery** | Power BI, DAX, Streamlit, Plotly — dashboards built for non-technical stakeholders |

---

## Featured work

Each project leads with the problem it solves. **Project titles link straight to the repo**; deeper writeups live on **[bharathnaveen.com](https://bharathnaveen.com)**.

### [Phishing Detection System](https://github.com/Bharath-Naveen/containerized-phishing-project)

`Data Scientist` · `ML Engineer` · `Forward Deployed Engineer`

**Problem:** Phishing sites appear and vanish faster than blocklists can react, and naive URL models over-flag legitimate, modern JavaScript-heavy pages.<br>
**Built:** A layered detection system — supervised ML triage (**LightGBM, XGBoost, Random Forest, Logistic Regression**) over **500K+** URL and host features, live page capture with **Playwright**, HTML/DOM behavior analysis, and a deterministic evidence-adjudication layer that returns explainable **safe / suspicious / phishing** verdicts. Containerized with **Docker**, deployed on **AWS**, and surfaced through a **Streamlit** dashboard.<br>
**Skills:** `Python` `LightGBM` `XGBoost` `Feature engineering` `Applied NLP` `Model evaluation` `Playwright` `Docker` `AWS` `Streamlit`

### [Cohort Analytics Platform](https://github.com/Bharath-Naveen/cohort-analytics)

`Data Analyst` · `ML Engineer` · `Forward Deployed Engineer`

**Problem:** University advisors had no fast way to see whether student cohorts were on track, behind, or ahead of their degree pace.<br>
**Built:** Designed and built the serverless data and ETL layer end to end — a containerized **Julia** ETL on **AWS ECS/Fargate**, degree-progress classification logic, **DynamoDB** with query-tuned indexes, a **Lambda** API, and multi-environment **CI/CD** — working directly with university stakeholders to ship it into production.<br>
**Skills:** `AWS Lambda` `DynamoDB` `ECS/ECR` `ETL pipeline design` `Data modeling` `CI/CD` `Julia` `Stakeholder delivery`

### [YouTube Comment Spam Detector](https://github.com/Bharath-Naveen/youtube-comment-spam-detector)

`Data Scientist` · `ML Engineer`

**Problem:** Harmful comments (phishing scams, bait bots, engagement spam) erode trust and distort engagement metrics, with no labeled dataset to learn from.<br>
**Built:** An end-to-end **NLP classification** pipeline — collected data via the **YouTube Data API**, generated labels with rule-based **weak supervision** plus manual validation, engineered behavioral features (link density, emoji frequency, repetition), and trained a **TF-IDF + logistic-regression** multi-class model tuned for high precision on the highest-risk categories.<br>
**Skills:** `Python` `Applied NLP` `TF-IDF` `scikit-learn` `Feature engineering` `Weak supervision` `Model evaluation` `API integration`

### [AutoRisk](https://github.com/Bharath-Naveen/AutoRisk) &nbsp;<sub>· in progress</sub>

`Data Scientist` · `ML Engineer` · `Forward Deployed Engineer`

**Problem:** First-time student buyers on a $5–10k budget can't easily judge which cheap used car is a reliable, safe bet.<br>
**Built:** A data product that ingests **NHTSA** complaints, recalls, and investigations, clusters failure patterns with **TF-IDF and KMeans**, models depreciation with **XGBoost**, and combines them into a composite **reliability score** served through a **Streamlit** app. Modular and Docker-ready.<br>
**Skills:** `Python` `XGBoost` `Applied NLP` `Clustering` `API ingestion` `Streamlit` `Docker`

---

## More projects

#### [BN Motors — SQL Data System](https://github.com/Bharath-Naveen/bn_motors_SQL)

`Data Analyst` · `Data Scientist`

**Problem:** A multi-store dealership's sales, service, financing, and parts data was siloed, with no reliable way to report on it.<br>
**Built:** Designed a normalized **26-table relational database** from the ER model up (**MySQL 8**), and wrote advanced analytical SQL (**joins, window functions, CTEs, subqueries**) plus reusable reporting views for inventory aging, gross-profit attribution, finance penetration, lead-to-sale funnels, and customer lifetime value.<br>
**Skills:** `MySQL` `SQL` `ER modeling` `Schema design` `Window functions` `CTEs` `Business reporting`

#### [Loan Default Prediction](https://github.com/Bharath-Naveen/german-loan-default-ml-)

`Data Scientist` · `Data Analyst`

**Problem:** Lenders need to flag likely defaulters early, on imbalanced credit data where accuracy alone is misleading.<br>
**Built:** A full supervised-learning workflow — EDA, preprocessing, and feature engineering on economic variables — then benchmarked **five models** (Logistic Regression, Decision Tree, Random Forest, SVM, Gradient Boosting) tuned for **recall and F1**, and surfaced the real risk drivers (low balances, short tenure, thin credit history).<br>
**Skills:** `Python` `scikit-learn` `Gradient Boosting` `Random Forest` `SVM` `Feature engineering` `EDA` `Imbalanced data` `Model evaluation`

#### [YouTube Analytics Pipeline](https://github.com/Bharath-Naveen/youtube-analytics-pipeline)

`Data Analyst`

**Problem:** Manually gathering YouTube performance data doesn't scale for trend and sentiment analysis.<br>
**Built:** An automated pipeline that extracts video and comment data via the **YouTube Data API**, structures views, likes, and comment text, stores it as JSON, and enables engagement-trend and sentiment analysis with **Plotly** visualizations.<br>
**Skills:** `Python` `YouTube Data API` `ETL` `Data cleaning` `EDA` `Plotly`

#### [TMDB Movie Scraper](https://github.com/Bharath-Naveen/tmdb-movie-scraper)

`Data Analyst`

**Problem:** Structured movie and review data isn't readily available for downstream analytics.<br>
**Built:** A web-scraping pipeline that extracts, cleans, and exports structured movie and review datasets ready for analysis.<br>
**Skills:** `Python` `BeautifulSoup` `Web scraping` `Data cleaning` `ETL`

---

## Experience

**Systems Engineer, Data & Analytics — Tata Consultancy Services** · 3+ years<br>
Built the **Power BI** dashboards, **SQL**, and **Python** reporting automation that Microsoft-account stakeholders made release decisions from, automated reporting pipelines that cut days of manual work per cycle, and ran exploratory analysis across hundreds of test and defect records, with a focus on data validation and cross-team communication. The enterprise-scale foundation behind everything above.

---

## Open to

`Data Scientist` · `Machine Learning Engineer` · `Data Analyst` · `Forward Deployed Engineer`

<div align="center">
  <img src="https://raw.githubusercontent.com/Bharath-Naveen/Bharath-Naveen/main/footer-anim.gif" alt="Turning messy data into decisions — bharathnaveen.com · linkedin.com/in/bharath-naveen · bharathnaveen.bn@gmail.com" width="100%">
</div>
