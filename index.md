---
layout: cv
title: Morgan Zhu's CV
---
# Morgan Zhu
Data mining engineer with 2 years of experience in risk control.

<div id="webaddress">
<a>+86 15952881126</a>
| <a href="morganzhurunzhe@gmail.com">MorganZhuRunzhe@gmail.com</a>
| <a href="https://morganzhurunzhe.github.io/markdown-cv/">Github</a>
| <a href="https://www.linkedin.com/in/morgan-zhu-107bab153/">Linkedin</a>
</div>



## Work
`2021/07 - 2023/06`
__SF Express__



## Education

`2023/02 - Current`
__The University of Sydney__

- Master of Information Technology(Software Engineering)

`2018/07 - 2021/05`
__The University of New South Wales__

- Master of Information Technology(Artificial Intelligence and Data Science and Engineering)

`2017/07 - 2018/07`
__The University of New South Wales__

- Study Abroad Program(Information System)

`2017/07 - 2018/07`
__Hebei University of Economics and Business__

- Bachelor of Finance




## Projects

### Claim Waybill Prediction
`Background`
For customers with a strong willingness to file claims and for consignments that are more prone to damage, our team predict the claim probability of the waybill on the fly and implement appropriate risk control strategies in advance.

`Solution`
- **1.** Implemented balanced data sampling and preprocessing pipeline on over a billion records with PySpark. 
- **2.** Developed the Deep and Cross Network (DCN) to learn feature interactions across different orders without manual feature engineering with PyTorch. 
- **3.** Containerized the DCN model as a RESTful API with FastAPI and Docker, deploying it to an internal PaaS. This setup achieved high concurrency and low latency, enabling efficient real-time inference.

`Impact`
Compared to the original rule-based model, the new deep learning model has tripled the precision under the same amount of recommended waybills. It also identifies 43% more high-risk waybills, ultimately increasing the average saved claim amount per waybill by 50%.

### Underweight Waybill Detection
`Background`
To mitigate revenue losses from delivery personnel underreporting consignment weights to seek higher commissions, our team developed a predictive model to flag suspect underweight waybills, enabling compliance staff to conduct targeted reweighing.

`Solution`
- **1.** Orchestrated a data processing pipeline leveraging Kafka, Spark Streaming, HBase, and Redis for real-time messaging, processing, enrichment, and feature retrieval.
- **2.** Developed a feature engineering pipeline to analyze time-series trends, seasonality, and encode high-cardinality categorical data using Word2Vec.
- **3.** Implemented a rule-based model for interpretable prediction. Supplemented it with an XGBoost model trained on over one billion waybills, tripling the precision of the baseline model.
- **4.** Automated the model re-training pipeline within a Spark ecosystem and persisted the model to HDFS regularly.
- **5.** Designed a dynamic data dashboard for inspection traffic monitoring, KPI tracking, and trend analysis to support swift decision-making. 

`Impact`
- **1.** Enhanced coverage to 53.9% for key segments including express delivery, fast freight, and international e-commerce, a significant leap from the previous 7.9%.
- **2.** Achieved a substantial financial impact by saving 120 million RMB in potential losses for the year 2023 through detective interventions informed by the model.

## Skills

### Data Application

### Data Engineering

### Software Engineering



<!-- ### Footer

Last updated: May 2024 -->


