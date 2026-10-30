<div align="center">

<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35">

# Hi, I'm Karthik Godugolla

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6AD3F7&center=true&vCenter=true&width=700&lines=Data+Engineer+%7C+AI+Engineer;Microsoft+Fabric+%7C+Databricks+%7C+dbt;Production+RAG+%26+Agentic+Systems;First+Author%2C+ML+Research+%40+RIT;M.S.+Data+Science+%40+RIT" alt="Typing SVG" />
</a>
<br/>

</div>

---

## About Me

Data and AI engineer with **3 years** building the pipelines and platforms that businesses
actually run decisions on. **M.S. Data Science, Rochester Institute of Technology** (GPA 3.76/4.0).

Most recently at **Fresenius Medical Care**, where I owned ingestion, transformation, and the
lakehouse and warehouse layers underneath enterprise reporting, in a HIPAA-regulated environment.
Alongside that I have been doing machine learning research at RIT since January 2025, where I am
first author on a paper currently in preparation.

- Built and maintained pipelines processing **5M+ records/day** and **2M+ events/day** across
  Salesforce, SAP, REST APIs and Kafka, transformed with **dbt** on **Microsoft Fabric** and
  **Databricks**
- Designed and shipped a **production RAG knowledge agent** end to end as sole developer:
  **47K+ documents**, **270K+ embedded chunks**, MCP server integration, gated by an
  **LLM-as-judge evaluation harness at 88% groundedness**
- Trained a 90-day patient risk model over **800+ engineered features** that cut attrition
  roughly **6%** in the targeted cohort against a holdout
- Replaced recurring manual reporting with self-serve Power BI and Streamlit analytics,
  returning around **20 analyst hours a week** to the team
- Deep interest in **CUDA, parallel computing**, and understanding why systems are slow
- Reach me at **karthik.godugolla@gmail.com**

---

## Research

**Scaling Synthetic Training Data for Mouse-Dynamics Authentication** — *first author, in preparation*
Rochester Institute of Technology · with C. Devlen and D. Hou

Built per-user BiLSTM models separating a genuine user from impostors never seen in training, and
established that generated training data measurably improves them, with **13 of 14 subjects
improving at p = 0.002**.

The contribution I care about most is the evaluation design. A device-level hardware difference,
not the behaviour being measured, was carrying the original result. Restricting comparison to a
matched hardware class moved one subject's error rate from **0.002 to 0.37**, meaning most of the
apparent effect had been artefact. Re-implemented TimeGAN in PyTorch and ran the full experimental
sweep on multi-worker GPU infrastructure with CUDA.

---

## Featured Projects

**Knowledge Agent — Production RAG over Internal Documentation**
*Azure OpenAI · RAG · MCP · Python · LLM-as-judge evaluation*
Designed and built end to end as sole developer, still in daily use. Grounded question answering
over 47K+ wiki and repository pages (270K+ embedded chunks), with MCP server integration for
on-demand tool calls. Answers cite sources and refuse explicitly when the documentation does not
support an answer, a control added after observing that users trust a confident wrong answer more
than an honest one. Evaluation harness measures groundedness at 88% and gates every release.

**Human vs. Agent Detection at Request Time**
*Python · scikit-learn · JavaScript · GroupKFold*
Classifier separating human from automated interaction across **27K traces and 56 users**
(**AUC 0.999**), running in-browser at **0.7ms per decision**, validated against live
browser-control agents. The interesting part was finding that a device-timing signal was leaking
group identity and inflating the score; removing those features raised unseen-hardware accuracy
from 94.9% to 96.2%.

**Cross-Attention Model for High-Dimensional Prediction** — *AIxBio Hackathon, Ginkgo Bioworks*
*PyTorch · custom loss · Parquet*
Cross-attention architecture built from scratch predicting responses across **12,995 output
dimensions** (~13.8M predictions), improving weighted MSE to **0.4344** against a 0.5536 baseline.
Redesigned the data pipeline mid-competition after hitting a ~65GB memory ceiling.

**GPU Programming with CUDA — N-Body Simulation & 2D Convolution**
*C++ · CUDA · OpenGL*
Custom CUDA kernels for an N-body simulation with grid/block tuning, double-buffered device memory
and real-time OpenGL rendering, plus GPU-accelerated 2D convolution over a custom tensor
abstraction using dynamic shared memory and atomic operations.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![SparkSQL](https://img.shields.io/badge/SparkSQL-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

**Data Engineering**

![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-003366?style=for-the-badge&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**AI / GenAI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/Azure%20OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**ML & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=python&logoColor=white)

**High Performance Computing**

![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![HPC](https://img.shields.io/badge/HPC-0071C5?style=for-the-badge&logo=intel&logoColor=white)

**BI & Cloud**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

<div align="center">

## Let's Connect

Always happy to talk about **data platforms**, **RAG and agentic systems**, **evaluation**, or **CUDA**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karthikgodugolla/)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:karthik.godugolla@gmail.com)

<br/>

*"The impediment to action advances action. What stands in the way becomes the way."* — Marcus Aurelius

![Wave](https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom.svg)

</div>
