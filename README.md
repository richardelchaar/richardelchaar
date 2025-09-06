
# I'm Richard. Welcome to my Portfolio!

My background in aerospace engineering trained me to solve complex problems with a first-principles, systems-level mindset. I've carried that same rigorous approach into the field of machine learning, where my focus is on bridging the gap between cutting-edge AI concepts and tangible business value.

I don't just build models; I engineer end-to-end solutions. My work spans the full ML lifecycle, from architecting scalable data infrastructure to deploying intelligent, automated systems that drive measurable impact.

-----

## 🌟 Featured Architectures

Here are the blueprints for some of the primary systems I've designed and built.

### [Advertis: The Anti-Ad Ad Platform](https://github.com/richardelchaar/advertis-platform)

> I built Advertis, a plug-and-play SDK designed to monetize any conversational app by re-imagining advertising. Instead of disruptive pop-ups, it connects to a backend that transforms ads into narrative enhancements that enrich the user's experience. To do this efficiently, I engineered a two-stage FastAPI microservice: a high-speed gatekeeper endpoint uses Redis for millisecond-fast safety and pacing checks, ensuring the expensive AI is only used on high-quality opportunities. If approved, the request is passed to the AI Creative Engine, a LangGraph multi-agent workflow that uses RAG to intelligently weave the perfect product placement into the conversation.

-----

### [AttritionGuard: The AI HR Strategist](https://github.com/richardelchaar/Employee-Attrition-MLOps)

> This platform goes beyond simply predicting *who* might leave; it uses a dual-core AI system to simulate the causal impact of retention strategies, answering the critical "what-if" questions for HR leaders. It's a proactive tool for data-driven talent management. My team and I engineered a self-healing, **end-to-end MLOps pipeline** built on **GitHub Actions** for CI/CD. It features an automated monitoring loop with **Evidently** that detects data drift and **automatically triggers model retraining and validation**, all served via **Dockerized microservices**.

-----

### [Featback: The Corporate Mind-Reader](https://github.com/richardelchaar/featback)

> This system translates the chaotic, unstructured "voice of the customer" from sources like Reddit into a structured, strategic asset. It moves beyond simple sentiment analysis to perform **Aspect-Based Emotion Analysis**, extracting not just *what* feature users are talking about, but the specific *emotion* and *root cause* behind their feedback. This is an **AI-powered ETL pipeline** orchestrated by **Airflow**, running a weekly job to pull data, process it via an LLM, and load structured Parquet files from **S3 into a Redshift data warehouse**, with all cloud infrastructure managed as code with **Terraform**.

-----

## 🔬 Some Other Projects

This is a selection of projects exploring core ML concepts and specialized data systems.

  * [Drone Telemetry Data Streaming Framework](https://github.com/richardelchaar/drone-telemetry-streaming)

    > Engineered a real-time data pipeline to process high-throughput drone telemetry, using a modern streaming stack **(Kafka, Spark Streaming, Cassandra)** to provide a foundation for live analytics and anomaly detection models.

  * [Multi-class Text Classification with Transformers](https://github.com/richardelchaar/Transformers-text-classification)

    > A deep dive into deploying modern NLP classifiers. I fine-tuned **BERT** on the **20 Newsgroups** dataset, then went beyond training to analyze its predictions with **LIME** and package it for production by exporting the model to **ONNX** and benchmarking its CPU inference speed.

  * [Unmasking Bias in Law Enforcement](https://github.com/richardelchaar/predicting-police-bias)

    > A data science project for social good that merges NYPD records with financial data to train a model predicting unjustified police actions. Used **feature importance analysis** to provide a quantitative tool for equity-focused reform.

  * [CIFAR-10/100 Image Classification with Compact ResNets](https://github.com/richardelchaar/ResNet9-image-classification)

    > A systematic ablation study on CNNs, demonstrating through rigorous experimentation that optimized training strategies and regularization can allow a compact **ResNet-9** to outperform a deeper model on a constrained budget.

  * [Shakespearean Text Generation with RNNs](https://github.com/richardelchaar/RNN-text-generation)

    > A foundational deep dive into sequence modeling. Implemented and benchmarked **LSTMs, GRUs, and vanilla RNNs** to compare architectures, training methods (Teacher Forcing), and generation techniques (Temperature Sampling vs. Beam Search).

-----

## 🛠️ My Core Competencies & Tech Stack

### Languages & Data Manipulation

  * **Python** (Pandas, NumPy, PySpark), **SQL**, Java, C++

### Machine Learning & AI

  * **Core ML:** Supervised & Unsupervised Learning, Causal Inference, Time-Series
  * **Generative AI:** RAG, Agentic AI, LLMs & Prompt Engineering (LangChain, LangGraph)
  * **Frameworks:** PyTorch, Scikit-Learn, SHAP, LIME

### Data Platforms & MLOps

  * **Cloud:** **Azure** (Azure ML, Databricks, Data Factory, Synapse), **AWS** (SageMaker, S3, Redshift)
  * **Tooling:** **MLflow**, **Airflow**, **Docker**, FastAPI, Delta Lake, Git, ChromaDB, ONNX
  * **Streaming:** Kafka, Spark Streaming

### Visualization & BI

  * **Power BI**, **Google Looker Studio**, Streamlit

-----

## 🎓 Education & Certifications

  * **Master of Management in Analytics** @ McGill University
  * **Bachelor of Engineering, Aerospace Engineering** @ Concordia University
  * **Microsoft Certified:** Azure Data Fundamentals
  * **Georgia Tech:** Intro to OOP with Java, Data Structures & Algorithms

-----

## 📫 Let’s Connect

  * [LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/richard-el-chaar-557ba8180/)
  * [Email](mailto:richard.elchaar@mail.mcgill.ca)
