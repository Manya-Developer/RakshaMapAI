# RakshaMapAI
RakshaMap AI — Project Description

RakshaMap AI is an AI-powered, GIS-based disaster management and decision-support platform designed to identify hazard-prone red zones, assess the vulnerability and carrying capacity of affected areas, and prioritize immediate relocation of at-risk habitations.

The platform integrates multi-hazard data such as floods, landslides, cyclones, earthquakes, rainfall, terrain/elevation, and historical disaster information with GIS, machine learning, and AI-based risk analysis. It evaluates each habitation based on hazard severity, population vulnerability, available resources, shelter capacity, and accessibility to generate a comprehensive risk assessment.

Based on the calculated risk and available capacity, RakshaMap AI can prioritize vulnerable habitations for relocation, identify suitable nearby shelters or safer locations, and support optimized emergency routing and resource allocation. The system is designed to help disaster-management authorities make faster, data-driven, and explainable decisions before and during emergencies.

Key Components
🗺️ GIS & Spatial Analysis — Mapping hazards, habitations, shelters, and safe zones.
🌊 Multi-Hazard Assessment — Floods, landslides, cyclones, earthquakes, rainfall, terrain, etc.
⚠️ Risk Engine — Combines hazard exposure and vulnerability to calculate habitation-level risk.
👥 Vulnerability Analysis — Identifies populations requiring higher priority during disasters.
🏠 Carrying Capacity Assessment — Determines whether shelters/safe locations can accommodate displaced populations.
🚨 Relocation Engine — Prioritizes habitations and recommends suitable relocation destinations.
🛣️ Emergency Routing — Supports safer and efficient routes considering disaster conditions.
🤖 AI Agents — Automates analysis, recommendations, and decision-support tasks.
📊 ML Models — Supports prediction, risk classification, evaluation, and continuous improvement.
🔄 Monitoring & Feedback — Uses updated information and feedback to improve decisions over time.


🛠️ Tools & Technologies

Backend & APIs

Python
FastAPI
REST APIs
SQLAlchemy
Pydantic

AI & Machine Learning

Machine Learning
AI Agents
Risk prediction and classification
Vulnerability assessment
Decision-support algorithms
Geospatial intelligence

GIS & Spatial Processing

PostgreSQL + PostGIS
Raster data processing
Shapefile processing
DEM (Digital Elevation Model)
Rainfall and hazard layers
Spatial risk analysis

Database & Caching

PostgreSQL
PostGIS
Redis

Frontend

React
Vite
JavaScript

Infrastructure & Deployment

Docker
Docker Compose

Testing & Development

Pytest
Git
GitHub
Jupyter Notebook
🚨 Core Modules
Multi-Hazard Detection — Identification and analysis of disaster-prone areas.
GIS-Based Risk Mapping — Spatial visualization of hazards, vulnerable habitations, shelters, and safe zones.
Vulnerability Assessment — Evaluation and prioritization of vulnerable populations.
Risk Engine — Combines hazard exposure and vulnerability to generate habitation-level risk scores.
Carrying Capacity Assessment — Evaluates whether shelters and safer locations can accommodate displaced populations.
Relocation Engine — Prioritizes habitations requiring relocation and identifies suitable destinations.
Emergency Routing — Determines safer and efficient routes during disaster scenarios.
Resource Allocation — Supports distribution and prioritization of emergency resources.
AI Agent Layer — Automates analysis and provides intelligent decision support.
Monitoring & Feedback — Enables continuous improvement using updated data and feedback.

The overall goal of RakshaMap AI is to transform complex disaster and geospatial data into actionable, explainable, and data-driven decisions, helping authorities identify high-risk habitations, plan safer relocation, optimize emergency response, and improve disaster preparedness.
