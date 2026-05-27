# Project Portfolio

[Back to README](./README.md) | [Research](./research.md) | [Experience](./experience.md)

This page collects selected AI, ML, robotics, multimodal AI, data engineering, and analytics projects. The main README gives the quick overview; these pages provide deeper project context.

## Project Snapshot

| Area | Project | Focus | Details |
|---|---|---|---|
| AI Education | AI-Assisted Robotics Learning Platform | LLM tutoring, robotics simulation, automated feedback | [Read case study](./docs/ai-assisted-robotics-platform.md) |
| Multimodal AI | Hate and Threat Detection in Digital Forensics | Image, OCR, text context, zero-shot classification, score fusion | [Read case study](./docs/multimodal-forensics-ai.md) |
| Production ML | Real Estate Valuation System | Computer vision, tabular ML, geospatial analytics, cloud pipelines | [Read case study](./docs/production-ml-real-estate.md) |
| Biomedical AI | Pump Prediction and Control Optimization | Time-series ML, genetic algorithms, calibration automation | [Read case study](./docs/biomedical-ml.md) |
| Python Tooling | pandas_eda_check | Reusable pandas-based exploratory data analysis package | [Read case study](./docs/pandas-eda-check.md) |
| Analytics | Business Intelligence and Data Analytics | Dashboards, retention analysis, business decision support | [Read case study](./docs/business-intelligence-data-analytics.md) |

## Public Projects

### Hate and Threat Detection in Digital Forensics

A multimodal AI pipeline for forensic evidence analysis using image evidence, OCR text, associated textual context, zero-shot classification, and score-level fusion.

- Built modality-aware workflows for image-only, OCR-based, and image-plus-context evidence analysis
- Used OpenCLIP, transformer-based zero-shot classification, frozen labels, structured outputs, and reproducible experiment scripts
- Designed the project for clear evaluation and repeatable experiments

**Tech:** Python, OpenCLIP, Hugging Face Transformers, OCR, pandas, pytest  
**Repository:** [Hate-and-Threat-Detection-in-Forensics](https://github.com/CS-Ponkoj/Hate-and-Threat-Detection-in-Forensics)

### pandas_eda_check

A lightweight Python package for fast exploratory data analysis with pandas.

- Published an installable Python package for quick inspection of missing values, unique values, and column completeness
- Designed as a reusable utility for messy tabular datasets and early-stage data analysis

```bash
pip install pandas-eda-check
```

**Tech:** Python, pandas, PyPI packaging  
**Repository:** [pandas_eda_check](https://github.com/CS-Ponkoj/pandas_eda_check)  
**PyPI:** [pypi.org/project/pandas-eda-check](https://pypi.org/project/pandas-eda-check)

## Research and Industry Projects

### AI-Assisted Robotics Learning Platform

A research-driven platform for robotics and programming education that combines structured learning content, browser-based coding, simulation, automated feedback, and LLM-based support.

**Tech:** Python, Flask, Flutter, ROS2, Gazebo, OpenAI APIs, unit testing, learning analytics  
**Details:** [AI-Assisted Robotics Learning Platform](./docs/ai-assisted-robotics-platform.md)

### Production ML and Real Estate Valuation System

An end-to-end machine learning system for real estate valuation and property intelligence using computer vision, tabular modeling, geospatial analysis, and cloud infrastructure.

**Tech:** Python, CatBoost, ResNet152V2, TensorFlow, AWS Lambda, AWS S3, AWS RDS, PostgreSQL, PostGIS  
**Details:** [Production ML and Real Estate Valuation System](./docs/production-ml-real-estate.md)

### Biomedical Time-Series ML and Control Optimization

A machine learning and optimization project focused on biomedical pump liquid transfer prediction and calibration automation.

**Tech:** Python, time-series modeling, genetic algorithms, benchmarking, monitoring  
**Details:** [Biomedical Time-Series ML and Control Optimization](./docs/biomedical-ml.md)

### Business Intelligence and Data Analytics

Analytics and BI work focused on customer behavior, supply-demand patterns, automation, and decision support.

**Tech:** Python, SQL, MySQL, Tableau, Power BI, data analysis  
**Details:** [Business Intelligence and Data Analytics](./docs/business-intelligence-data-analytics.md)
