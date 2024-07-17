<center>

# TED ZHAO

416-551-622  ⋄  zp4work@gmail.com\
10/4 Sheppards Lane, Norwood SA 5067, Australia\
[linkedin.com/in/ted-zhao](https://linkedin.com/in/ted-zhao) ⋄ [github.com/tade0726](https://github.com/tade0726)

</center>


## Machine Learning Engineer / Data Scientist

- Over 5 years of experience in Machine Learning and Data Science, specializing in finance, travel, and retail sectors. Demonstrates a robust ability to deliver end-to-end ML solutions enriched with deep business insights.
- Extensive experience in developing computer vision solutions and building high-performance recommendation systems, notably for click-through rate models at Skyscanner.
- Proven track record in customer segmentation analysis and demographic profiling, adept in conducting A/B testing. Capable of flexibly integrating various statistical and machine learning methods to derive user insights and support routine business monitoring.


## WORK EXPERIENCE

### ML Engineer/Data Scientist - Skyscanner

<p style="text-align:left;font-style: italic">
    Shenzhen, China (Collaborated with EU teams)
    <span style="float:right;font-style: italic">
        Nov 2019 - July 2021
    </span>
</p>

**Computer Vision / Deep Learning**

Implemented deep learning models on hotel imagery to enhance the user experience in **Pytorch**, designing an efficient workflow for image collection and labeling critical for deploying computer vision technologies.

- Leveraged ResNet to categorize hotel images into 20 detailed landscape and interior labels. Improved differentiation of similar categories by embedding nuanced business logic, resulting in a hierarchical labeling system that achieved **99% accuracy** in Top-5 predictions.
- Utilized MobileNet to refine thumbnail selection for hotels, focusing on aesthetic appeal and detail. This approach evolved aesthetic evaluation from a single-dimensional to a multi-dimensional framework, using semantic analysis and object recognition to enhance image selection, culminating in a **+3% increase in click-through rate (CTR)** after implementing the new strategy.

**Recommendation Systems**
- Developed and continuously refined recommendation systems using iterative machine learning models, including Logistic Regression, LightGBM, and Deep Learning. This involved a comprehensive cycle of model development from data collection and feature engineering to training and deployment.
- Implemented **Docker** for seamless end-to-end model deployment and development within an **AWS Sagemaker** environment, leading to a **5-10% increase in CTR** with each iteration.
  
**ETL**
Developing and maintaining data flows supplementing the recommendation system

- Developed and maintained T+1 batch data processes, capturing long-term patterns in user behaviors. Utilized AWS Lambda to trigger Python scripts written in PySpark, storing data in Parquet format within a Databricks environment. This setup supports both model training and real-time inference needs.
- Engineered a real-time data streaming solution capturing user log data from Elasticsearch, facilitating the immediate tracking of user click behaviors. Implemented a Redis key-value store for rapid data access, integrating this stream with batch data to enhance the real-time data feed for inference. This integration improved the Click-Through Rate (CTR) by 2%, significantly impacting core profitability metrics.

---
### ML/DATA Engineer - RAINMAKR.AI

<p style="text-align:left;font-style: italic">
    Sydney, NSW(remote)
    <span style="float:right;font-style: italic">
May 2023 – Now
    </span>
</p>

**LLM Application for Financial Analysis**

- **Semantic Analysis**: Implemented advanced semantic analysis using LLMs for prompt engineering. Developed customized prompts to accurately categorize company descriptions and news feeds, facilitating the extraction of GICS-like themes. This process enhances the understanding of company genres and industries, providing a structured overview of corporate landscapes.
- **RAG Graph with LLM**: Pioneered the development of a knowledge graph utilizing LLM's robust parsing capabilities. Analyzed and extracted a variety of entities and their relationships from company news and descriptions, including executives, competitors, and product logistics chains. This information was integrated into a graph database, supporting a Retrieval-Augmented Generation (RAG) system for enhanced information retrieval and decision-making accuracy in financial contexts.


**Developing finaicial strategy with ML algorithem**

- Explored the integration of alpha factors derived from robust financial domains with machine learning algorithms. This approach involved iterating from decision tree models to reinforcement learning, creating a comprehensive ML lifecycle encompassing data ingestion, feature engineering, model training, and prediction. The key innovation was the use of reinforcement learning to develop a unified framework that simultaneously directs both bidding strategies and investment amounts, optimizing portfolio management for enhanced yield.

**ETL**

- Reduced original schema size by over 50% by designing and simplifying data models involving 30+ tables using the DBT framework, enhancing maintainability and system performance.
- Aligned date ranges across various data models to minimize batch data volumes, transforming disorganized schemas into deduplicated, well-documented models. Achieved a 15% reduction in redundant data storage, enhancing data retrieval efficiency.
- Conducted thorough analysis to identify and resolve bottlenecks in data flow. Improved system efficiency by re-indexing and aligning data types of join keys, and refining join conditions, resulting in a 50% reduction in query runtime.
- Implemented Slowly Changing Dimensions (SCD) principles to create reliable backup checkpoints, ensuring data integrity in catastrophic scenarios. Introduced an incremental update strategy for table ingestion, saving 10% in data ingestion time.
- Integrated DBT with Dagster Cloud to develop a mixed orchestration framework combining notebook and DBT jobs. This approach unified heterogeneous data streams, enhancing the user interface and overall data presentation within the DBT framework.


---

### Data Scientist - DJI

<p style="text-align:left;font-style: italic">
Shenzhen, China
    <span style="float:right;font-style: italic">
April 2018 - Aug 2018
    </span>
</p>

**Pre-sale Competitive Analysis for an Educational Product**
- Supported a comprehensive marketing campaign by conducting an in-depth competitive analysis.
	- Analyzed the demographics of dozens of potential cities in China, assessing factors such as economic conditions and demographic data, supplemented with competitor information regarding the location and distribution of their stores.
    - Developed a customized ranking strategy/algorithm to prioritize our distribution across target cities, incorporating both quantitative data and intuitive business factors.
- Collected all relevant data independently using a custom web crawler built with **Scrapy** in Python.

**Data Reports for Sales Monitoring**
- Continuously monitored sales post-product launch, analyzing internal data on user demographics, including location, income, and age, to create detailed customer segment analyses.
- Analyzed datasets to identify patterns and insights, supporting the campaign team in strategic planning.
- Provided stakeholders with critical data and analysis, empowering informed decision-making and optimizing the product launch strategy.

**Django Development**
- Developed a Django-based API for a Jupyter integration extension, enabling seamless SQL querying and data model management.
- Designed the API to enhance Jupyter extension capabilities for efficient SQL query execution.
- Managed and standardized data models using Django and SQLAlchemy, ensuring data consistency across the platform.

---

### Data Scientist - Smart Decision Technology Ltd

<p style="text-align:left;font-style: italic">
Shenzhen, China
    <span style="float:right;font-style: italic">
[Aug 2015 - Mar 2018]
    </span>
</p>

**Credit Risk Modeling**
- Designed credit scorecard workflows using Python to replace SAS.
- Created **feature selection, binning, and WOE calculation** in Python.
- Converted the logistics model into scorecards in Python.

**Simulation**
- Designed and implemented a Python-based simulation system for S.F. Express.
- Leveraged **SimPy** to accurately model the conveyor system within the Distribution Centre.
- Created an intuitive front-end interface, enabling business users to input site designs and parameters with ease.
- Developed a robust back-end service using **Flask**, which stored simulation parameters and results for each iteration, utilizing **SQLAlchemy** for efficient model management.
- The solution surpassed three competitors in terms of speed and adaptability, securing a **2-year contract** with S.F. Express.


## RESEARCH PROJECT

### Quantitative Trading with Reinforcement Learning - The University of Adelaide

<p style="text-align:left;font-style: italic">
Adelaide, SA, Australia
    <span style="float:right;font-style: italic">
Sep 2022 - Feb 2023
    </span>
</p>

**Reinforcement Learning** 
- Conducting a research project while pursuing a master's degree in Machine Learning at The University of Adelaide.
- Developed a trading strategy for the Crypto market using **Reinforcement Learning**.
- Designed a reward system with Sharp Ratio, where actions were the next sell/buy quantity of all assets.
- Created **two Deep Learning modules** to capture price signals and market sentiment.

**Back Testing** 
- Developed a back-test with metrics **Sharp Ratio, Maximum Drawdown(MDD)** and presented profit curves with plots, considering fees and compound returns.


## Education

|  | Institution | Duration |
| --- | --- | --- |
| Master of Machine Learning | The University of Adelaide | June 2021 - May 2023 |
| Bachelor's Degree in Mathematical Sciences | Shenzhen University | September 2010 - July 2014 |


## Certifications

|  | Date | Verification |
| --- | --- | --- |
| Machine Learning - Coursera | October 2016 | [Verify](https://www.coursera.org/account/accomplishments/verify/Q89DMB9RYYTB) |
| Machine Learning Nanodegree Program - Udacity | December 2018 | [Verify](https://graduation.udacity.com/confirm/PKAQPLU2) |

## Language Proficiency

|  | Proficiency |
| --- | ---: |
| English | IELTS 7.0 |
| Mandarin | Native |
| Cantonese | Native |


## SKILLS
|  | |
| --- |:---|
| **AI/Machine Learning** | Reinforcement Learning, Deep Learning, Clustering, Lightgbm, XGBoost, SVM, Word2Vec|
| **Data Engineer** | DBT, Databricks, Snowflakes |
| **Data Science** | Tableau, A/B Testing, Statistics, Data Analysis |
| **Programming Languages** | Python, VBA, Scala, Julia |
| **MLOPS/Cloud** | AWS Sagemaker, Azure ML, AWS|
| **Web/Web Scraping** | Django, Flask, asyncio, Scrapy|
| **ETL** | SQL, SQLAlchemy, Spark, Pandas |
| **Version Control** | Git |
| **Containerization** | Docker|
