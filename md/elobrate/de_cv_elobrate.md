<center>

# TED ZHAO

416-551-622  ⋄  ted.zhao.au@gmail.com\
10/4 Sheppards Lane, Norwood SA 5067, Australia\
[linkedin.com/in/ted-zhao](https://linkedin.com/in/ted-zhao) ⋄ [github.com/tade0726](https://github.com/tade0726)

</center>


## Data Engineer

- 3+ year of experiences in ETL workflows and data orchestration, familiar with Azure, AWS and Databricks to create full data circle, data ingesting, data transformation, data enrichment and refined for advanced analysis.
- Skilled in transitioning data operations to modern platforms like Dagster and DBT, establishing scalable CI/CD pipelines that support extensive data handling and performance needs.
- Led significant projects at Rainmakr.ai and Skyscanner, focusing on advanced SQL optimizations and dynamic data pipeline development, which substantially reduced processing times and enhanced real-time analytics.

## Skills
- **Data Engineering**: DBT, Databricks, Snowflakes, Dagster
- **ETL**: SQL, SQLAlchemy, Spark, Pandas
- **AI/Machine Learning**: Reinforcement Learning, Deep Learning, Clustering, Lightgbm, XGBoost, SVM, Word2Vec, AB-Test
- **MLOPS/Cloud**: Azure ML, AWS, Sagemaker, MLflows
- **Data Science**: Tableau, A/B Testing, Statistics, Data Analysis
- **Programming Languages**: Python, VBA, Scala, Julia
- **Web Development/Web Scraping**: Django, Flask, asyncio, Scrapy
- **Version Control**: Git
- **Containerization**: Docker


## WORK EXPERIENCE

### Data/AI Engineer - Rainmakr.ai (A finance startup based in Sydney)

<p style="text-align:left;font-style: italic">
    Adelaide, SA(remote)
    <span style="float:right;font-style: italic">
May 2023 – July 2024
    </span>
</p>

**ETL**

- Reduced original schema size by over 50% by designing and simplifying data models involving 30+ tables using the DBT framework, enhancing maintainability and system performance.
- Aligned date ranges across various data models to minimize batch data volumes, transforming disorganized schemas into deduplicated, well-documented models. Achieved a 15% reduction in redundant data storage, enhancing data retrieval efficiency.
- Conducted thorough analysis to identify and resolve bottlenecks in data flow. Improved system efficiency by re-indexing and aligning data types of join keys, and refining join conditions, resulting in a 50% reduction in query runtime.
- Implemented Slowly Changing Dimensions (SCD) principles to create reliable backup checkpoints, ensuring data integrity in catastrophic scenarios. Introduced an incremental update strategy for table ingestion, saving 10% in data ingestion time.
- Integrated DBT with Dagster Cloud to develop a mixed orchestration framework combining notebook and DBT jobs. This approach unified heterogeneous data streams, enhancing the user interface and overall data presentation within the DBT framework.

**LLM Application for Financial Analysis**

- Leveraged LLMs for advanced semantic analysis in prompt engineering, developing tailored prompts to accurately categorize company descriptions and news feeds. This methodology facilitated the extraction of GICS-like themes, enhancing the understanding of company genres and industries for a structured corporate landscape overview.
- Innovated in creating a knowledge graph utilizing LLM's robust parsing capabilities to analyze and extract a diverse array of entities and their relationships from company news and descriptions, such as executives, competitors, and product logistics chains. Integrated this data into a graph database to support a Retrieval-Augmented Generation (RAG) system, significantly improving information retrieval and decision-making accuracy in financial contexts.

---

### Machine Learning Engineer - Skyscanner (one of the largest flight ticket search engines in Europe)

<p style="text-align:left;font-style: italic">
    Shenzhen, China (Collaborated with EU teams)
    <span style="float:right;font-style: italic">
        Nov 2019 - July 2021
    </span>
</p>

**ETL**

- Developed and maintained T+1 batch data processes, capturing long-term patterns in user behaviors. Utilized AWS Lambda to trigger Python scripts written in PySpark, storing data in Parquet format within a Databricks environment. This setup supports both model training and real-time inference needs.
- Engineered a real-time data streaming solution capturing user log data from Elasticsearch, facilitating the immediate tracking of user click behaviors. Implemented a Redis key-value store for rapid data access, integrating this stream with batch data to enhance the real-time data feed for inference. This integration improved the Click-Through Rate (CTR) by 2%, significantly impacting core profitability metrics.

**Recommendation Systems**
- Developed and improved recommendation systems using iterative ML models (Logistic Regression / LightGBM / Deep learning).
- Utilized **Docker** for end-to-end model delivery with **AWS Sagemaker** environment, resulting in a **+5-10% increase in CTR** with each iteration.

**Computer Vision / Deep Learning**
- Applied Deep learning models to hotel images to enhance user experience.
- Employed ResNet for categorizing hotel images into 20 landscape/interior labels, achieving **99% accuracy** in Top-5 predictions.
- Utilized MobileNet to select thumbnails for hotels, resulting in a **+3% increase in CTR**.

---

### Data Scientist - DJI (the world's largest drone manufacturer)

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
Aug 2015 - Mar 2018
    </span>
</p>

**Credit Risk Modeling**
- Designed credit scorecard workflows in Python, replacing SAS
- Implemented **feature selection, binning, and WOE calculation**
- Converted logistic models into scorecards using Python

**Simulation System Development**
- Built Python-based simulation for S.F. Express using **SimPy**
- Created user-friendly frontend for business users
- Developed **Flask** backend with **SQLAlchemy** for data management
- Outperformed competitors, securing 2-year contract

**HKJC Member Segmentation Analysis**
- Applied **K-Means clustering** for member segmentation
- Developed targeted strategies based on lifecycle analysis
- Presented actionable insights through data visualisation

**NLP-Based Sentiment Analysis**
- Developed sentiment analysis for Chinese app reviews
- Implemented custom tokenization for Chinese text
- Used **Word2Vec** and **K-means clustering** for thematic analysis
- Built supervised learning model for sentiment classification

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
- **Master of Machine Learning**, The University of Adelaide (June 2021 - May 2023)
- **Bachelor's Degree in Mathematical Sciences**, Shenzhen University (September 2010 - July 2014)

## Certifications
- Machine Learning - Coursera (October 2016)
  [Verify](https://www.coursera.org/account/accomplishments/verify/Q89DMB9RYYTB)
- Machine Learning Nanodegree Program - Udacity (December 2018)
  [Verify](https://graduation.udacity.com/confirm/PKAQPLU2)

## Language Proficiency
- English: IELTS 7.0
- Mandarin: Native
- Cantonese: Native