---
permalink: /
title: "Victor Coscrato"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /resume
  - /cv
---

{% include base_path %}

About me
======
Placeholder

Education
======
* Ph.D in Artificial Intelligence (2019 – 2024) – University College Cork, Ireland.
* Master in Statistics (2018 – 2019) – Universidade Federal de São Carlos / Universidade de São Paulo, Brazil.
* Bachelor in Statistics (2014 – 2017) - Universidade Federal de São Carlos, Brazil.

Work experience
======
* FI GROUP (09/2024 – Current): Data science Analyst
  * Lead the end-to-end development and deployment of AI products to enhance consultancy operations, including solutions integrating Large Language Models (LLMs). Responsibilities encompassed full-stack development, designing intuitive frontends (UI/UX), building robust backends with seamless database and ML/AI model integration, and ensuring production-ready deployments.

* KEELVAR, CORK – IRELAND (04/2021 – 08/2021): AI/ML Analyst
  * Design and implementation of an end-to-end supplier recommender system.

* STONE PAGAMENTOS SA, BRAZIL (06/2017 – 12/2017): People Analytics Analyst
  * Responsible for automating the selection of candidates in selection processes.
  * Creation of metrics and models for employee evaluation.

  
Skills
======
* Extensive knowledge of various fields of artificial intelligence: Recommendation Systems, Computer Vision, Natural Language Processing (NLP), Deep Learning (DL), People Analytics.
* Vast knowledge in statistical modeling: Linear/Logistic regression and classification, Neural networks, Random Forest, SVMs, Ensembles, etc.
* Experience in developing innovative AI solutions utilizing large language models (LLMs).
* AI/ML/Statistics Tools and Libraries: 
  * Python and its AI/ML ecosystem: PyTorch, TensorFlow, Keras, Scikit-learn, Pandas, PySpark, XGBoost, OpenCV, etc.
  * R and its analytics and statistical modeling tools: Tidyverve (dplyr, tidyr, tibble, purrr, tidymodels, etc.), Caret, mlr3.
  * Data Visualization Tools in Python and R: Matplotlib, seaborn, ggplot2.
* AI in Production – Tools and technologies for deployment and scaling:
  * Docker, Kubernetes for containerization and orchestration.
  * SQL, MongoDB for database integration in AI workflows.
  * APIs (e.g. FastAPI) for serving AI models in production environments.
  * Cloud platforms: Google Cloud, Amazon AWS, Microsoft Azure.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
