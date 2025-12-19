---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi 👋 I am Aishwarya and I love to learn. I studied Computer Science and Economics at UMass Amherst. I have professional experience in data science, data management, building data pipelines, and curating creative visualizations. 

I like to read about research in machine learning and computation. I love to write content for a general technical audience on my [blog](https://medium.com/@platform-10). My goal is to explain concepts, model architecture, performance, and takeaways in a simpler way. I also like to make keychains out of old CPUs and other PCBs.

Skills 💻
------
**Languages:** Python, Javascript, Java, C, SQL, Bash

**Frameworks:** Spring, React, Node

**ETL & Data Managament:** Snowflake ❄️, dbt, Airflow, Hadoop, Spark

**MLOps:** Run.AI, TFX

**Cloud & Tools:** Azure (Document Intelligence, Blob Storage), AWS (Kinesis, Redshift, S3, Sagemaker)

**Analytics & Visualization:** Tableau, Streamlit, PowerBI


**DeepLearning.AI Certifications**:
* Hyperparameter Tuning, Regularization, and Optimization - [Certificate](https://coursera.org/share/158f8da97c13a817b465325ab9536ea1)
* Machine Learning in Production - [Certificate](https://coursera.org/share/077f5d5935bd3daafb890ebf1f739dd3)
* Data Modeling, Transformation and Serving - [Certificate](https://coursera.org/share/79c3537a89f460390cd504d589169d71)


Projects
-----

**Hanabi-LLM Multi-Agent:**

Built a council-based multi-agent LLM system for the cooperative, imperfect-information game Hanabi, drawing on the LLM-Hanabi: [Evaluating Multi-Agent Gameplays with Theory-of-Mind and Rationale Inference in Imperfect Information Collaboration Game](https://www.alphaxiv.org/abs/2510.04980) benchmark (Liang et al., 2025). The approach decomposes decision-making into specialized agents for playing, hinting, and discarding, each performing probabilistic belief updates over hidden card states using Bayesian reasoning from public observations, hints, and discard information. It also implements deterministic greedy strategies such as maximizing clue efficiency and protecting critical cards to support controlled comparisons and strategy evaluation. An orchestrator coordinates agent execution, while a final decision agent aggregates structured recommendations and confidence scores to choose actions under uncertainty. The system is implemented in Python on DeepMind’s Hanabi Learning Environment with configurable OpenAI-compatible LLM backends.

**DeepLearning.AI Data Engineering Capstone:** *AWS Glue, Apache Iceberg, Redshift, Terraform, dbt, Airflow*

Extracted and transformed semi-structured data from Spotify API and relational data from operational databases. Developed a 3-tier data lake, using Iceberg for transformation, Redshift Spectrum and dbt for serving, and Glue and Terraform for orchestration

**DataOps Bastion Host Implementation:** *AWS - EC2, RDS, Cloud9, Route 53, Terraform*

Configured private subnets for data resources and public subnets for the bastion host. Utilized NAT Gateway for internet access. Created corresponding SSH key pairs for the bastion host's connectivity. Configured security groups to ensure proper access.

**Central Logging Monitor:** *React, Cypress, SpringBoot*

Served as an integration liaison for a workflow monitoring tool, allowing drill-down functionality for ISO New England. Wrote integration tests with Cypress, covering page routing and redirects

