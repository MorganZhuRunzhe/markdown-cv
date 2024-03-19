---
layout: cv
title: Morgan Zhu's CV



---

# Morgan Zhu

Data mining engineer with 2 years of experience in risk control.

<div id="webaddress">
<a>+61 452166575</a>
| <a href="morganzhurunzhe@gmail.com">MorganZhuRunzhe@gmail.com</a>
| <a href="https://morganzhurunzhe.github.io/markdown-cv/">Github</a>
| <a href="https://www.linkedin.com/in/morgan-zhu-107bab153/">Linkedin</a>
</div>




## Work

`2021 - 2023`
__SF Express - Data Mining Engineer__

- **1.** Achieved a **120 million** RMB reduction in potential revenue losses by deploying an underweight waybill detection model, combined with the data processing pipeline, which expanded suspect waybill detection coverage from **7.9%** to **53.9%**.
- **2.** Enhanced operational efficiency and financial performance by developing the claim waybill prediction model, which **tripled** the precision of the baseline model and identified **43%** more high-risk waybills, ultimately boosting average claim savings per waybill by **50%**.
- **3.** Collaborated with frontline staff and public security to develop a drug detection model, overcoming an extremely imbalanced data challenge (**imbalance ratio: 10 : 30,000,000 * 365**). The new model increased recall rate by **200%**, significantly enhancing corporate social responsibility.



## Education

`2023 - Current`
__The University of Sydney__

- Master of Information Technology(Software Engineering)

`2018 - 2021`
__The University of New South Wales__

- Master of Information Technology(Artificial Intelligence and Data Science and Engineering)

`2017 - 2018`
__The University of New South Wales__

- Study Abroad Program(Information System)

`2014 - 2017`
__The Hebei University of Economics and Business__

- Bachelor of Finance



## Skills

`Application`

- Machine Learning with Interpertability
- Machine Learning with Imbalanced Data
- Deep Learning with Structured Data
- Data Visualization
- Data Analysis

`Engineering`

- Batch Processing: Hive SQL, Spark SQL, DBT
- Streaming Processing: Spark Streaming
- Data Warehouse: Hive, Snowflake
- Development: Python(Django, FastAPI)
- Deployment: Docker
- CI/CD: Github



## Projects

### Underweight Waybill Detection

`Background`
To mitigate revenue losses from delivery personnel under-reporting consignment weights to seek higher commissions, our team developed a predictive model to flag suspect underweight waybills, enabling compliance staff to conduct targeted reweighing.

`Solution`

- **1.** Orchestrated a data processing pipeline leveraging Kafka, Spark Streaming, HBase, and Redis for real-time messaging, processing, enrichment, and feature retrieval.
- **2.** Developed a feature engineering pipeline to analyze time-series trends, seasonality, and encode high-cardinality categorical data using Word2Vec.
- **3.** Implemented a rule-based model for interpretable prediction. Supplemented it with an XGBoost model trained on over one billion waybills, tripling the precision of the baseline model.
- **4.** Automated the model re-training pipeline within a Spark ecosystem and persisted the model to HDFS regularly.
- **5.** Designed a dynamic data dashboard for inspection traffic monitoring, KPI tracking, and trend analysis to support swift decision-making. 

`Impact`
By leveraging model-informed interventions, the project significantly expanded coverage to 53.9% (up from 7.9%) across key segments like express delivery, fast freight, and international e-commerce, and saved 120 million RMB in potential losses for 2023.



### Claim Waybill Prediction

`Background`
For customers with a strong willingness to file claims and for consignments that are more prone to damage, our team predict the claim probability of the waybill on the fly and implement appropriate risk control strategies in advance.

`Solution`

- **1.** Implemented a balanced data sampling and preprocessing pipeline on over a billion records with PySpark, for model performance and stability. 
- **2.** Developed the Deep and Cross Network (DCN) to learn feature interactions across different orders without manual feature engineering with PyTorch. 
- **3.** Containerized the DCN model as a RESTful API with FastAPI and Docker, deployed on an internal PaaS for robust real-time inference.

`Impact`
Compared to the baseline model, the deep learning model has tripled the precision and identified 43% more high-risk waybills, boosting the average claim savings per waybill by 50%, significantly impacting operational efficiency and financial performance.



<!-- ### Footer

Last updated: May 2024 -->
