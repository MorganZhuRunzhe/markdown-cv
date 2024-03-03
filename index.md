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
For customers with a strong willingness to file claims and for consignments that are more prone to damage, we predict the claim probability of the waybill on the fly and implement appropriate risk control strategies in advance.

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
- * Developed a streaming data processing and enrichment workflow that integrates several key technologies—Kafka for messaging, Spark Streaming for processing, HBase for enrichment, and Redis for fast feature access.
- **2.** Developed a feature engineering pipeline, focusing on extracting trend and seasonality information from time-series data and embedding categorical data with high cardinality into compact vectors via a pre-trained Word2Vec model.
- **3.** Developed a pre-defined rule-based model for interpretable prediction of an underweight waybill and also trained and fine-tuned an XGBoost model on over one billion waybills, achieving a threefold increase in precision compared to the baseline model.
- **4.** Automated the XGBoost model re-training pipeline within a Spark ecosystem and persisted the model to HDFS regularly.
- **5.** Designed and implemented a dynamic data dashboard for traffic monitoring, KPI tracking, and trend visualizations, to support swift decision-making. 

`Impact`
- **1.** Covered 53.9% of waybills under the product segments of express delivery, fast freight, and international e-commerce (the older solution's coverage was 7.9%).
- **2.** Saved a total of 120 million RMB in losses in 2023.

## Skills

### Data Application

### Data Engineering

### Software Engineering



<!-- ### Footer

Last updated: May 2024 -->


