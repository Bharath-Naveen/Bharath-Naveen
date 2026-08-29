<div align="center">
  <img src="https://raw.githubusercontent.com/Bharath-Naveen/Bharath-Naveen/main/github-header-anim_1.gif" alt="Bharath Naveen, Data Scientist, ML Engineer, Data Analyst, Forward Deployed Engineer" width="100%">
</div>

<p align="center">
  <a href="https://bharathnaveen.com"><img src="https://img.shields.io/badge/Portfolio-bharathnaveen.com-0E7C86?style=flat&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/bharath-naveen/"><img src="https://img.shields.io/badge/LinkedIn-0E7C86?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="mailto:bharathnaveen.bn@gmail.com"><img src="https://img.shields.io/badge/Email-0E7C86?style=flat&logo=gmail&logoColor=white"></a>
</p>

## About me

I build **end-to-end data and machine learning systems**, from database design and ETL pipelines to modeling, evaluation, and production deployment. I came to data through mechanical engineering and **3+ years of enterprise analytics at Tata Consultancy Services**, so I care as much about clean pipelines, data validation, and clear communication as I do about the model itself. I hold an **MS in Information Science (Machine Learning)** from the University of Arizona, and I'm open to **Data Scientist, Machine Learning Engineer, Data Analyst, and Forward Deployed Engineer** roles.

Full writeups on **[bharathnaveen.com](https://bharathnaveen.com)**.

| Core stack | |
| --- | --- |
| **Languages** | Python (pandas, NumPy, scikit-learn), SQL (CTEs, window functions), R, Julia |
| **ML & modeling** | scikit-learn, XGBoost, LightGBM, applied NLP, model evaluation |
| **Data & cloud** | AWS (Lambda, DynamoDB, S3, ECS/ECR), ETL design, ER modeling |
| **BI & delivery** | Power BI, DAX, Streamlit, Plotly |

---

## Featured work

<table>
<tr><th align="left"><a href="https://github.com/Bharath-Naveen/containerized-phishing-project">Phishing Detection System</a> &nbsp; <sub>Data Scientist · ML Engineer · FDE</sub></th></tr>
<tr><td>
<b>Problem:</b> Phishing sites appear and disappear within hours, faster than blocklists can react, and naive URL classifiers over-flag legitimate, modern JavaScript-heavy pages.<br>
<b>Built:</b> A layered detection system combining supervised ML triage (<b>LightGBM, XGBoost, Random Forest, Logistic Regression</b>) over <b>500K+</b> URL and host features, live page capture with <b>Playwright</b>, HTML and DOM behavior analysis, and a deterministic evidence-adjudication layer that returns explainable safe, suspicious, or phishing verdicts. Containerized with <b>Docker</b>, deployed on <b>AWS</b>, and surfaced through a <b>Streamlit</b> dashboard.<br>
<b>Skills:</b> <code>Python</code> <code>LightGBM</code> <code>XGBoost</code> <code>Feature engineering</code> <code>Applied NLP</code> <code>Model evaluation</code> <code>Playwright</code> <code>Docker</code> <code>AWS</code> <code>Streamlit</code>
</td></tr>
</table>

<table>
<tr><th align="left"><a href="https://github.com/Bharath-Naveen/cohort-analytics">Cohort Analytics Platform</a> &nbsp; <sub>Data Analyst · ML Engineer · FDE</sub></th></tr>
<tr><td>
<b>Problem:</b> University advisors had no fast, reliable way to see whether student cohorts were on track, behind, or ahead of their degree pace.<br>
<b>Built:</b> Designed and built the serverless data and ETL layer end to end: a containerized <b>Julia</b> ETL on <b>AWS ECS/Fargate</b>, degree-progress classification logic, <b>DynamoDB</b> with query-tuned indexes, a <b>Lambda</b> API, and multi-environment <b>CI/CD</b>. Delivered into production working directly with university stakeholders.<br>
<b>Skills:</b> <code>AWS Lambda</code> <code>DynamoDB</code> <code>ECS/ECR</code> <code>ETL pipeline design</code> <code>Data modeling</code> <code>CI/CD</code> <code>Julia</code> <code>Stakeholder delivery</code>
</td></tr>
</table>

<table>
<tr><th align="left"><a href="https://github.com/Bharath-Naveen/youtube-comment-spam-detector">YouTube Comment Spam Detector</a> &nbsp; <sub>Data Scientist · ML Engineer</sub></th></tr>
<tr><td>
<b>Problem:</b> Harmful comments such as phishing scams, bait bots, and engagement spam erode trust and distort engagement metrics, and there was no labeled dataset to learn from.<br>
<b>Built:</b> An end-to-end <b>NLP classification</b> pipeline that collects data via the <b>YouTube Data API</b>, generates labels with rule-based <b>weak supervision</b> plus manual validation, engineers behavioral features (link density, emoji frequency, repetition), and trains a <b>TF-IDF and logistic-regression</b> multi-class model tuned for high precision on the highest-risk categories.<br>
<b>Skills:</b> <code>Python</code> <code>Applied NLP</code> <code>TF-IDF</code> <code>scikit-learn</code> <code>Feature engineering</code> <code>Weak supervision</code> <code>Model evaluation</code> <code>API integration</code>
</td></tr>
</table>

<table>
<tr><th align="left"><a href="https://github.com/Bharath-Naveen/AutoRisk">AutoRisk</a> &nbsp; <sub>in progress · Data Scientist · ML Engineer · FDE</sub></th></tr>
<tr><td>
<b>Problem:</b> First-time student buyers on a $5k to $10k budget cannot easily judge which cheap used car is a reliable, safe bet.<br>
<b>Built:</b> A data product that ingests <b>NHTSA</b> complaints, recalls, and investigations, clusters failure patterns with <b>TF-IDF and KMeans</b>, models depreciation with <b>XGBoost</b>, and combines them into a composite <b>reliability score</b> served through a <b>Streamlit</b> app. Modular and Docker-ready.<br>
<b>Skills:</b> <code>Python</code> <code>XGBoost</code> <code>Applied NLP</code> <code>Clustering</code> <code>API ingestion</code> <code>Streamlit</code> <code>Docker</code>
</td></tr>
</table>

---

## More projects

<table>
<tr><th align="left"><a href="https://github.com/Bharath-Naveen/bn_motors_SQL">BN Motors SQL Data System</a> &nbsp; <sub>Data Analyst · Data Scientist</sub></th></tr>
<tr><td>
<b>Problem:</b> A multi-store dealership's sales, service, financing, and parts data was siloed across systems, with no reliable way to report on it.<br>
<b>Built:</b> A normalized <b>26-table relational database</b> designed from the ER model up (<b>MySQL 8</b>), plus advanced analytical SQL (joins, <b>window functions, CTEs</b>, subqueries) and reusable reporting views for inventory aging, gross-profit attribution, finance penetration, lead-to-sale funnels, and customer lifetime value.<br>
<b>Skills:</b> <code>MySQL</code> <code>SQL</code> <code>ER modeling</code> <code>Schema design</code> <code>Window functions</code> <code>CTEs</code> <code>Business reporting</code>
</td></tr>
</table>

<table>
<tr><th align="left"><a href="https://github.com/Bharath-Naveen/german-loan-default-ml-">Loan Default Prediction</a> &nbsp; <sub>Data Scientist · Data Analyst</sub></th></tr>
<tr><td>
<b>Problem:</b> Lenders need to flag likely defaulters early, on imbalanced credit data where accuracy alone is misleading.<br>
<b>Built:</b> A full supervised-learning workflow covering EDA, preprocessing, and feature engineering on economic variables, then benchmarked <b>five models</b> (Logistic Regression, Decision Tree, Random Forest, SVM, Gradient Boosting) tuned for <b>recall and F1</b>, surfacing the real risk drivers such as low balances, short tenure, and thin credit history.<br>
<b>Skills:</b> <code>Python</code> <code>scikit-learn</code> <code>Gradient Boosting</code> <code>Random Forest</code> <code>SVM</code> <code>Feature engineering</code> <code>EDA</code> <code>Imbalanced data</code> <code>Model evaluation</code>
</td></tr>
</table>

<table>
<tr><th align="left"><a href="https://github.com/Bharath-Naveen/youtube-analytics-pipeline">YouTube Analytics Pipeline</a> &nbsp; <sub>Data Analyst</sub></th></tr>
<tr><td>
<b>Problem:</b> Manually gathering YouTube performance data does not scale for trend and sentiment analysis.<br>
<b>Built:</b> An automated pipeline that extracts video and comment data via the <b>YouTube Data API</b>, structures views, likes, and comment text, stores it as JSON, and enables engagement-trend and sentiment analysis with <b>Plotly</b> visualizations.<br>
<b>Skills:</b> <code>Python</code> <code>YouTube Data API</code> <code>ETL</code> <code>Data cleaning</code> <code>EDA</code> <code>Plotly</code>
</td></tr>
</table>

<table>
<tr><th align="left"><a href="https://github.com/Bharath-Naveen/tmdb-movie-scraper">TMDB Movie Scraper</a> &nbsp; <sub>Data Analyst</sub></th></tr>
<tr><td>
<b>Problem:</b> Structured movie and review data is not readily available for downstream analytics.<br>
<b>Built:</b> A web-scraping pipeline that extracts, cleans, and exports structured movie and review datasets ready for analysis, with a repeatable flow for refreshing the data.<br>
<b>Skills:</b> <code>Python</code> <code>BeautifulSoup</code> <code>Web scraping</code> <code>Data cleaning</code> <code>ETL</code>
</td></tr>
</table>

---

## Experience

**Systems Engineer, Data & Analytics, Tata Consultancy Services** · 3+ years<br>
Built the Power BI dashboards, SQL, and Python reporting automation that Microsoft-account stakeholders made release decisions from, automated reporting pipelines that cut days of manual work per cycle, and ran exploratory analysis across hundreds of test and defect records, with a focus on data validation and cross-team communication. The enterprise-scale foundation behind everything above.

---

## Open to

`Data Scientist` · `Machine Learning Engineer` · `Data Analyst` · `Forward Deployed Engineer`

<div align="center">
  <img src="https://raw.githubusercontent.com/Bharath-Naveen/Bharath-Naveen/main/footer-anim_1.gif" alt="Turning messy data into decisions. bharathnaveen.com, linkedin.com/in/bharath-naveen, bharathnaveen.bn@gmail.com" width="100%">
</div>
