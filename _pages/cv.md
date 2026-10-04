---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
{% include toc %}

Please find the PDF version of my CV [here](../files/BryanZang_resume.pdf).

Education
======
* Bachelor of Mathematics --- University of Waterloo (Jun 2024)
  * Majors in Honours Statistics and Honours Computational Mathematics
  * Minor in Computer Science
  * Relevant courses:
    * Probability, Statistics, Stochastic Processes, Linear Algebra, Neural Networks, Microeconomics, Macroeconomics, Advanced Regression, Estimation & Hypothesis Testing, Databases, Algorithms, Graph Theory, Optimization, Generalized Linear Models

Certifications
======
* Bloomberg Market Concepts --- Bloomberg
  * Portfolio Management, Fixed Income, FX, Equities, Options, Commodities, Terminal Basics
* Microsoft Certified: Azure AI Fundamentals --- Microsoft
  * Recognized for fundamental knowledge of machine learning (ML) and artificial intelligence (AI) concepts and familiarity with technologies such as Kubernetes and other related basic cloud services.
  * Applied concepts towards natural language processing (NLP), facial recognition, object detection, and image classification.

Work Experience
======
* Research Assistant --- Bank of Canada (Apr 2026)
  * Analyzed market-risk indicators using the Canadian Overnight Repo Rate Average in Databricks and PowerBI to support interactive risk monitoring and model analysis.
  * Streamlined big data ingestion frameworks from multiple internal warehouses in Fabric to ensure robustness of data availability.
  * Developed agentic analytical tools through Copilot studio to assess model risk documentation and compliance controls for the Bank's Market Data Management research curve.
  * Documented and validated structural tests on cross-currency swap operations collaborating with 5 central banks to maintain the consistency and transparency of market workflows.

* Research Assistant --- Bank of Canada (Jul 2025)
  * Debt Management team under Markets and Banking Department
  * Analyzed large financial-market datasets using Pyspark, Databricks, and PowerBI to support research on [Government of Canada debt](https://www.canada.ca/en/department-finance/services/publications/debt-management-report/2024-2025.html), [market well-being](https://www.bankofcanada.ca/wp-content/uploads/2026/05/fsr2026.pdf), investor behavior, policy reporting, and [debt-distribution framework revisions](https://publications.gc.ca/collections/collection_2026/banque-bank-canada/FB3-8-2026-18-eng.pdf).
  * Developed a daily volume-weighted bond-specialness indicator using Python and security-level transaction data to measure relative demand and scarcity in the Government of Canada bond market.
  * Reduced runtime efficiency of data pipelines by 100 fold using code parallelization and data structure serialization.
  * Quantified hedge fund positions and foreign central banks' holdings of Government of Canada securities into dedicated time series to analyze the growing foreign investment in Canadian debt and their inherent risks

Projects
======
* Canadian Bond Market Flow Report and Positions Tracker --- Bank of Canada Internal Tool
  * Developed a participant-level positions framework by integrating primary and secondary markets data using Databricks and Python, enabling daily tracking of outstanding bonds and their market flows and position changes.
  * Built an interactive auction-participation dashboard in PowerBI with configurable reporting windows to monitor and regulate dealer and customer activity and also gain insight for investor relations.
  * Implemented entity-level aggregation and trade-booking logic in SQL to reconcile identity, positions, and flows across multiple data sources.
* Spatial Models for Canadian Temperature Inference
  * Compared spline regression, polynomial regression, and generalized additive models (GAMs) for statistical spatial inference of annual Canadian temperatures using R and the gamair package.
  * Evaluated performance using generalized cross-validation and R² where GAM scored strongest with 17.83 and 0.89 respectively.
* Tumor Modeling with HTCs and iNKT Cells
  * Extended a nonlinear differential-equation model describing tumor and immune cell interactions by implementing numerical simulations in MATLAB.
  * Analyzed equilibrium behavior and changes in system dynamics using phase-plane, stability, and Hopf Bifurcation analyses.
* Linear Pogramming - Simplex Implementation
  * Implemented various theories and computations from A Gentle Introduction to Optimization (Guenin, Konemann, and Tuncel).
  * Applied theories including Simplex algorithm, Bland’s Rule, two-phase Simplex, and duality theory.

Personal
======
* Programming:
  * Python, SQL, R, MATLAB, Julia, Java, C/C++, JavaScript, LaTeX, HTML/CSS
* Technologies:
  * Numpy, Pandas, Pyspark, scikit-learn, TensorFlow, Plotly, Matplotlib
* Softwares:
  * Excel, PowerBI, Databricks, Git, Copilot Studio, Refinitiv, Bloomberg Terminal, Jupyter, Fabric, Power Automate
* Languages:
  * Native/bilingual proficiency in English and Chinese
* Interests:
  * Photography, hiking, puzzles, tea enthusiast, trivia lover


<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
