Data Science Internship Capstone Repository | Author:Malik MAnoranjan
Data Science Project Implementation Specialist

 Project Overview
This repository houses the complete end-to-end implementation of an enterprise data science project (Customer Churn Prediction & Analytics). It demonstrates the full project lifecycle across 6 distinct phases—moving from initial strategic planning and data ingestion to machine learning model development, production containerization, continuous performance monitoring, and final project documentation.

Repository Architecture
```text
churn-prediction-internship/
│
├── data/
│   ├── raw/                      # Immutable raw data files (CSV)
│   └── processed/                # Cleaned and normalized datasets ready for modeling
│
├── docs/
│   ├── project_plan.docx         # Week 1: Strategic Planning & Scoping Deliverable
│   ├── data_acquisition_strategy.docx # Week 2: Data Acquisition & Preprocessing Report
│   ├── week_3_model_development_report.docx # Week 3: Model Development Report
│   ├── week_4_deployment_report.docx # Week 4: Deployment & Integration Strategy
│   ├── week_5_performance_evaluation_report.docx # Week 5: Performance & Optimization Report
│   └── week_6_final_capstone_report.docx # Week 6: Comprehensive Final Capstone Report
│
├── src/                          # Modular Python source code package
│   ├── __init__.py
│   ├── config.py                 # Centralized configuration and file paths
│   ├── data_preprocessing.py     # Week 2: Data cleaning, missing values, and normalization
│   ├── train_model.py            # Week 3: Model training, validation splits, and metrics
│   ├── app.py                    # Week 4: FastAPI production web service endpoint
│   ├── evaluate_performance.py   # Week 5: KPI monitoring, latency tracking, and alerts
│   └── main.py                   # Week 6: Master orchestrator running the entire pipeline
│
├── Dockerfile                    # Containerization instructions for production deployment
├── requirements.txt              # Project dependencies
└── README.md                     # Repository landing page & documentation
