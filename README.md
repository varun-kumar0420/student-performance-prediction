# Student Performance Prediction Using Python and Machine Learning

## 📌 Project Overview

The **Student Performance Prediction** project is a Data Science and Machine Learning project designed to analyze student-related data and predict student academic performance or identify students who may be at risk of poor performance.

The project follows a step-by-step Data Science workflow, starting from project planning and exploratory data analysis (EDA), followed by data preprocessing, feature engineering, model development, evaluation, and documentation.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze student academic and behavioral data.
- Identify important factors affecting student performance.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values, duplicates, invalid values, and outliers.
- Create meaningful features for Machine Learning.
- Develop Machine Learning models for student performance prediction.
- Evaluate models using appropriate performance metrics.
- Compare different Machine Learning algorithms.
- Identify students who may require additional academic support.
- Document the complete Data Science workflow.

---

## 📂 Project Scope

The project will focus on the following areas:

1. Project Planning and Strategy
2. Data Collection
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis
5. Data Visualization
6. Feature Engineering
7. Machine Learning Model Development
8. Model Evaluation
9. Result Analysis
10. Final Documentation

---

# 📅 Weekly Progress

## ✅ Week 1 – Data Science Project Planning and Strategy Design

**Status: Completed**

During Week 1, the overall project strategy and implementation plan were prepared.

### Work Completed

- Defined the project problem statement.
- Defined project objectives.
- Identified project scope.
- Planned the Data Science workflow.
- Identified potential data sources and variables.
- Planned data preprocessing activities.
- Planned Exploratory Data Analysis.
- Planned feature engineering.
- Planned Machine Learning models.
- Defined the model evaluation approach.
- Prepared project architecture and workflow diagrams.
- Created a project timeline.

### Planned Machine Learning Models

The following models are planned for the project:

- Logistic Regression
- Decision Tree
- Random Forest

### Planned Evaluation Metrics

The models will be evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross-Validation

### Week 1 Deliverables

- `Week_1_Data_Science_Project_Plan.docx`
- `Week_1_Data_Science_Project_Plan_Varun_Kumar.pdf`
- `architecture_diagram.png`
- `timeline_chart.png`
- `workflow_diagram.png`

---

# 📊 Week 2 – EDA and Visualization Framework

**Status: Completed**

Week 2 focused on designing a detailed **Exploratory Data Analysis and Visualization Framework** for the Student Performance Prediction project.

The purpose of this phase is to understand the structure, quality, distribution, and relationships within the dataset before applying Machine Learning algorithms.

### Work Completed

#### 1. Exploratory Data Analysis Planning

The EDA framework covers:

- Dataset structure
- Dataset dimensions
- Data types
- Missing values
- Duplicate records
- Invalid values
- Outliers
- Variable distributions
- Correlations
- Relationships between variables
- Target-class distribution

#### 2. Data Types Identified

Potential variables were categorized into:

- Numerical variables
- Categorical variables
- Ordinal variables
- Binary variables
- Date/Time variables
- Text variables

#### 3. Univariate Analysis

Individual variables will be analyzed using:

- Histograms
- KDE plots
- Box plots
- Bar charts
- Count plots

Example variables:

- Study hours
- Attendance
- Marks
- Gender
- Academic support
- Performance/risk class

#### 4. Bivariate Analysis

Relationships between two variables will be investigated using:

- Scatter plots
- Box plots
- Grouped bar charts
- Stacked bar charts

Examples include:

- Study hours vs marks
- Attendance vs marks
- Academic support vs performance
- Activity participation vs marks

#### 5. Multivariate Analysis

Multiple variables will be analyzed using:

- Correlation heatmaps
- Pair plots
- Grouped summaries
- Interaction analysis

Potential interactions include:

- Attendance × Study Hours
- Attendance × Previous Performance
- Academic Average × Attendance

#### 6. Missing Data and Outlier Analysis

The framework includes:

- Missing-value percentage calculation
- Duplicate detection
- Domain validation
- IQR-based outlier detection
- Box-plot-based analysis
- Justified treatment of missing values and outliers

#### 7. Visualization Strategy

Different visualizations will be selected according to the question being investigated.

| Analysis | Visualization |
|---|---|
| Distribution | Histogram / KDE |
| Category comparison | Bar / Count Plot |
| Numerical relationship | Scatter Plot |
| Outlier detection | Box Plot |
| Correlation | Heatmap |
| Target distribution | Bar / Count Plot |
| Group comparison | Box / Violin Plot |
| Interactive analysis | Plotly |

#### 8. Feature Engineering Readiness

The EDA framework also identifies potential features for later Machine Learning stages, including:

- Academic Average
- Assessment Gap
- Study Effort Index
- Attendance Bands
- Study-Hour Bands
- Interaction Features
- One-Hot Encoded Categorical Features

Data leakage will also be considered so that future information is not incorrectly used as a predictor.

#### 9. Model Evaluation Readiness

The planned evaluation workflow includes:

```text
Data Cleaning
      ↓
Train/Test Split
      ↓
Preprocessing
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Cross-Validation
      ↓
Model Evaluation
      ↓
Final Test Set
Model Evaluation
        ↓
Insights & Recommendations


