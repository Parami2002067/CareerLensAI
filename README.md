# CareerLens AI 🚀

**CareerLens AI** is a data-driven technology career intelligence and skill-gap analysis project designed to help users understand how their existing skills align with current technology career requirements.

The project analyzes a large collection of real-world job postings to identify career demand, employer skill requirements, career-specific skill patterns, and potential skill gaps.

The long-term goal of CareerLens AI is to allow a user to select a target career, provide their current skills or resume, and receive a personalized career match score, missing skill recommendations, learning priorities, and alternative career suggestions.

---

## Project Objectives

CareerLens AI aims to:

* Analyze demand for technology careers.
* Identify frequently requested technical and professional skills.
* Understand how skill requirements differ between career domains.
* Build a standardized technology skill knowledge base.
* Compare user skills with industry requirements.
* Identify skill gaps for selected careers.
* Recommend relevant skills to learn next.
* Suggest alternative technology career paths based on user capabilities.

---

## Dataset Overview

The original dataset contains:

* **1,615,940 job postings**
* **23 original attributes**

After preprocessing and technology-job filtering:

* **275,022 technology job postings**
* **24 attributes**
* **11 technology career domains**

The additional `Career Domain` feature was created during preprocessing to classify technology jobs into broader career areas.

### Career Domains

The project currently includes the following career domains:

* Software Development
* Data & Analytics
* Cybersecurity
* Cloud & DevOps
* Networking
* Database
* UI/UX Design
* Business Analysis
* IT Management
* Quality Assurance
* Software Delivery & Agile Management

---

## Data Processing Pipeline

The CareerLens workflow currently follows this process:

```text
Raw Job Dataset
      ↓
Data Exploration
      ↓
Technology Job Filtering
      ↓
Career Domain Classification
      ↓
Skill Standardization
      ↓
Skill Extraction
      ↓
Technology Market Analysis
      ↓
Career-Specific Skill Analysis
      ↓
Career Matching & Skill Gap Analysis
```

---

## Technology Market Analysis

The current analysis focuses on understanding overall technology career demand and employer skill requirements.

### Technology Jobs Analyzed

**275,022**

### Standardized Skills Identified

**95**

A rule-based skill extraction process was developed using Python and regular expressions to transform semi-structured employer skill descriptions into standardized skill labels.

---

## Skill Extraction Validation

The extraction process was progressively tested and refined before being applied to the complete dataset.

| Validation Stage              |                  Result |
| ----------------------------- | ----------------------: |
| Initial 50-record validation  |            96% coverage |
| Initial 500-record validation |            97% coverage |
| Refined 500-record validation |           100% coverage |
| Full technology dataset       | 100% detection coverage |

> Detection coverage refers to whether at least one standardized skill was identified in a job posting. It should not be interpreted as complete extraction accuracy.

---

## Most Frequently Requested Skills

The current standardized skill-frequency analysis identified the following as some of the most frequently requested skills across technology job postings.

| Rank | Skill                | Job Postings |
| ---: | -------------------- | -----------: |
|    1 | SQL                  |       58,833 |
|    2 | Problem Solving      |       52,168 |
|    3 | Python               |       52,114 |
|    4 | Data Analysis        |       38,050 |
|    5 | Java                 |       31,468 |
|    6 | Network Security     |       31,449 |
|    7 | CSS                  |       31,251 |
|    8 | HTML                 |       31,251 |
|    9 | Quality Assurance    |       27,938 |
|   10 | JavaScript           |       27,837 |
|   11 | Data Visualization   |       27,738 |
|   12 | Security Protocols   |       24,549 |
|   13 | Tableau              |       24,268 |
|   14 | Communication Skills |       20,987 |
|   15 | React                |       20,944 |
|   16 | Statistical Analysis |       20,940 |
|   17 | Power BI             |       20,876 |
|   18 | Incident Response    |       17,526 |
|   19 | CCNA                 |       17,470 |
|   20 | Angular              |       17,427 |

These results represent skill demand within the analyzed dataset.

---

## Key Findings

The current analysis reveals several important patterns:

* **SQL** is the most frequently identified standardized skill within the analyzed technology job postings.
* **Python** and **Problem Solving** also show very strong demand.
* Data-related skills including **Data Analysis, Data Visualization, Tableau, Statistical Analysis, and Power BI** appear prominently.
* Software development technologies such as **Java, HTML, CSS, JavaScript, React, and Angular** are strongly represented.
* Cybersecurity and networking competencies including **Network Security, Security Protocols, Incident Response, and CCNA** appear among the most frequently requested skills.
* Professional competencies such as **Problem Solving** and **Communication Skills** remain important alongside technical knowledge.

The results indicate that technology career readiness depends on a combination of technical, analytical, and professional competencies rather than programming skills alone.

---

## Most In-Demand Technology Careers

Some of the most frequently occurring roles identified during the technology market analysis include:

| Rank | Career Role               | Job Postings |
| ---: | ------------------------- | -----------: |
|    1 | Network Administrator     |       17,470 |
|    2 | Quality Assurance Analyst |       10,541 |
|    3 | Database Administrator    |       10,482 |
|    4 | Data Analyst              |       10,406 |
|    5 | Backend Developer         |       10,404 |
|    6 | Frontend Developer        |       10,308 |
|    7 | UX/UI Designer            |        7,028 |
|    8 | Network Security Analyst  |        7,027 |
|    9 | Data Scientist            |        7,003 |
|   10 | IT Project Manager        |        6,974 |

---

## Technologies Used

### Data Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook / Google Colab

### Data Processing

* Regular Expressions
* Text Normalization
* Rule-Based Skill Extraction
* Career Classification
* Data Cleaning

### Development & Documentation

* Git
* GitHub
* HTML
* CSS
* JavaScript

---

## Repository Structure

```text
CareerLens-AI/
│
├── notebooks/
│   ├── 01_Data_Exploration.ipynb
│   ├── 02_Data_Preprocessing.ipynb
│   └── 03_Technology_Market_Analysis.ipynb
│
├── data/
│   └── processed technology datasets
│
├── README.md
│
└── additional project files
```

The repository structure may continue to evolve as CareerLens AI is developed.

---

## Current Project Status

### Completed

* Initial dataset exploration
* Technology job filtering
* Career domain classification
* Technology career-demand analysis
* Standardized skill knowledge base
* Rule-based skill extraction
* Skill extraction validation
* Overall technology skill-demand analysis

### In Progress

* Career-domain-specific skill analysis
* Role-specific skill requirements
* Career profile construction

### Planned

* User skill input
* Resume skill extraction
* Career Match Score
* Skill-gap identification
* Learning recommendations
* Alternative career suggestions
* CareerLens AI user interface

---

## Next Phase

The next stage of the project focuses on answering:

> **How do skill requirements differ between technology career paths?**

The results will be used to create career-specific skill profiles that can later support CareerLens AI's personalized career matching and skill-gap recommendation system.

---

## Project Purpose

CareerLens AI is being developed as both a data analytics project and a career intelligence application.

It demonstrates practical skills in:

* Data preprocessing
* Exploratory data analysis
* Business-oriented data analysis
* Text processing
* Rule-based information extraction
* Data visualization
* Career taxonomy design
* Requirement analysis
* Insight generation
* AI-assisted product development

---

## Author

**G.C. Parami Ashinsa Hemasiri**

BSc in Information and Communication Technology
Rajarata University of Sri Lanka

Career interests: **Business Analysis | Data Analytics | AI & Technology**

---

## Project Status

🚧 **CareerLens AI is currently under active development.**

Additional career intelligence, skill-gap analysis, recommendation features, and application components will be added as the project progresses.
