# Project Portfolio

[Back to README](./README.md) · [Research](./research.md) · [Experience](./experience.md) · [Live portfolio](https://ponkojshill.csponkoj.chatgpt.site/)

Selected research, open-source, and production projects are organized by evidence: public code, live demonstrations, publications, measurable outcomes, or professional experience.

## Featured Systems

| Dates | System | Scope | Evidence |
|---|---|---|---|
| Aug 2022–Present | **AI-Assisted TDD for Robotics Learning** | Automated evaluation, telemetry, ROS2/Gazebo simulation, guardrailed LLM tutoring | [Case study](./docs/ai-assisted-robotics-platform.md) · [IEEE paper](https://doi.org/10.1109/FIE61694.2024.10893417) |
| May 2026–Present | **AI-Assisted PCB Design** | Natural-language requirements, validated hardware artifacts, interactive review | [Case study](./docs/ai-assisted-pcb-design.md) · [Live demo](https://ai-assisted-pcb-design.streamlit.app/) · [Repository](https://github.com/CS-Ponkoj/AI-Assisted-PCB-Design) |
| Nov 2025–Dec 2025 | **Hate and Threat Detection in Digital Forensics** | OCR, OpenCLIP, DeBERTa, evidence routing, auditable score fusion | [Case study](./docs/multimodal-forensics-ai.md) · [Repository](https://github.com/CS-Ponkoj/Hate-and-Threat-Detection-in-Forensics) |
| Jun 2021–Aug 2022 | **Property Valuation and Geospatial Risk** | CatBoost, ResNet152V2, PostGIS, AWS, multimillion-record pipelines | [Case study](./docs/production-ml-real-estate.md) · [Experience](./experience.md#machine-learning-engineer--data-team-lead) |
| Jan 2024–May 2024 | **Biomedical Pump Prediction and Control** | Time-series forecasting, genetic algorithms, monitoring, cloud pipelines | [Case study](./docs/biomedical-ml.md) · [Experience](./experience.md#ai-software-engineer-intern) |
| Public package | **pandas-eda-check** | Data-quality assessment and dataset profile comparison | [Case study](./docs/pandas-eda-check.md) · [PyPI](https://pypi.org/project/pandas-eda-check/) · [Repository](https://github.com/CS-Ponkoj/pandas_eda_check) |

## Research System

### AI-Assisted TDD for Robotics Learning

An NSF-funded research platform combining browser-based robotics programming, automated evaluation, behavioral telemetry, ROS2/Gazebo simulation, and guardrailed LLM tutoring.

- **Built:** unit tests, hidden checks, real-time failure analysis, telemetry, simulation, and tutoring workflows
- **Measures:** pass rates, attempts, time-to-recovery, edit-run cycles, accuracy, robustness, and learner experience
- **Scale:** deployed learning components supporting 100+ students
- **Status:** platform development complete; experimental evaluation in progress
- **Tech:** Python, Flask, Flutter, ROS2, Gazebo, OpenAI APIs, automated testing, learning analytics

[Read the case study](./docs/ai-assisted-robotics-platform.md)

## Generative AI and Engineering Automation

### AI-Assisted PCB Design

A generative engineering prototype that converts natural-language sensor-board requirements into validated, structured hardware artifacts.

- Produces component selections, BOM, pin map, netlist, power budget, schematic/layout notes, and interactive PCB visualization
- Supports deterministic base parsing, local Ollama models, and Gemini API extraction
- Validates model outputs and rejects unsupported requests rather than fabricating hardware
- Provides source-grounded PCB review and exports to CSV, Markdown, and JSON
- **Tech:** Python, Streamlit, Gemini, Ollama, Graphviz, structured validation, pytest

[Try the live system](https://ai-assisted-pcb-design.streamlit.app/) · [Open the repository](https://github.com/CS-Ponkoj/AI-Assisted-PCB-Design) · [Read the case study](./docs/ai-assisted-pcb-design.md)

## Multimodal AI

### Hate and Threat Detection in Digital Forensics

A case-driven forensic pipeline that analyzes embedded text, associated messages, and image-only evidence and produces auditable fused risk scores.

- Routes image-only, OCR, and associated-text evidence through modality-aware workflows
- Uses OpenCLIP and DeBERTa-based zero-shot classification
- Preserves frozen labels, structured outputs, and reproducible experiment scripts
- Combines modality scores in an explicit fusion stage
- **Tech:** Python, OpenCLIP, Hugging Face Transformers, DeBERTa, OCR, pandas, pytest

[Open the repository](https://github.com/CS-Ponkoj/Hate-and-Threat-Detection-in-Forensics) · [Read the case study](./docs/multimodal-forensics-ai.md)

## Production ML and Geospatial Intelligence

### Property Valuation and Geospatial Risk

Professional work at Softwrd Ltd combining predictive modeling, computer vision, geospatial analytics, and cloud data processing.

- Developed CatBoost valuation and ResNet152V2 image-classification workflows
- Automated processing for 8M+ images and analysis of 4M+ property records
- Evaluated property locations across 100+ geographical risk zones using PostgreSQL/PostGIS
- Built AWS Lambda, S3, RDS, and ETL workflows
- Contributed to $20K in government funding and valuation results that exceeded Zillow benchmarks

The production source is private; the case study documents architecture, ownership, scale, and results without exposing proprietary code or data.

[Read the case study](./docs/production-ml-real-estate.md)

### Related Production Projects

| Dates | Project | Contribution |
|---|---|---|
| May 2022–Jun 2022 | Norwegian Mapping Authority Property Valuation | Built boosting-based valuation workflows and multimillion-record cloud/document-database processing |
| Jan 2022–Mar 2022 | Automated Valuation Model | Developed CatBoost property-price and rental-value models on approximately 3M records |
| Nov 2021–Dec 2021 | Risk Report of Norway | Intersected property locations with environmental and geographic risk layers using a cloud-hosted spatial database |

## Biomedical AI

### Pump Prediction and Control Optimization

Professional work at Consynsys Technologies using time-series forecasting and optimization to improve biomedical pump control.

- Developed forecasting models for liquid-transfer behavior
- Applied genetic algorithms to pump-control optimization
- Reduced manual calibration effort by approximately 50%
- Added real-time monitoring, predictive-maintenance analytics, and benchmarking
- Designed AWS/GCP data and AI workflows for scalable processing and engineering analysis

[Read the case study](./docs/biomedical-ml.md)

## Open-Source ML Tooling

### pandas-eda-check

A tested Python package for inspecting a DataFrame and comparing meaningful data-profile changes between reference and current datasets.

- Reports schema, missing-data, duplicate-rate, numerical, datetime, and categorical changes
- Handles empty frames, nullable dtypes, mixed objects, unhashable values, infinities, and all-null columns
- Returns pandas DataFrames for programmatic use
- Includes tests, CI, packaging metadata, and a public PyPI release

```bash
pip install pandas-eda-check
```

[Open PyPI](https://pypi.org/project/pandas-eda-check/) · [Open the repository](https://github.com/CS-Ponkoj/pandas_eda_check) · [Read the case study](./docs/pandas-eda-check.md)

## Business Intelligence and Analytics

Analytics work across healthcare, logistics, and product strategy:

- Healthcare dashboards, SQL datasets, data models, repeatable ETL workflows, and Microsoft Fabric integration
- Regression and supply-demand analysis that contributed to a 15% improvement in customer retention
- Tableau and Power BI dashboards for operational planning, campaigns, product decisions, and stakeholder reporting

[Read the BI case study](./docs/business-intelligence-data-analytics.md) · [View professional experience](./experience.md)
