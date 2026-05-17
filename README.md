# data-quality-pipeline
A data  A quality pipeline that validates, cleans, and reports issues in supplier product datasets before ML training.

A production-style data validation pipeline built to simulate real-world ML data engineering workflows.
This project ingests product data from multiple suppliers, standardizes inconsistent formats, validates records, tracks failures with detailed reporting, and determines whether the final dataset is safe for machine learning training.

Features:
- Multi-source product data ingestion
- Data cleaning and normalization
- Schema and value validation
- Failure tracking and reporting
- Dataset quality metrics
- ML training readiness checks
- Structured logging system

Why I Built This: 
Most beginner data projects stop at analysis.
I wanted to build something closer to the systems that exist before machine learning models are even trained where data reliability, validation, and monitoring matter just as much as the model itself.
This project helped me practice:
- writing cleaner production-style Python
- thinking like a data engineer
- designing modular validation systems
- handling imperfect real-world data

