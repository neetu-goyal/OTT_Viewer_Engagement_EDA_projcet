# OTT Viewer Engagement & Retention Risk Analysis

## Project Overview

This project focuses on analyzing viewer engagement patterns, episode-level viewing behavior, and drop-off risk in an Over-The-Top (OTT) streaming platform environment.

The objective is to identify content characteristics and viewing patterns associated with higher engagement and potential episode drop-offs using Exploratory Data Analysis (EDA), statistical summaries, and data visualization.

The project uses a synthetic OTT dataset designed for educational and portfolio purposes. It does not contain proprietary or actual Hotstar viewer data.

## Business Problem

OTT platforms need to understand how viewers interact with streaming content to improve content performance and viewing experiences.

This project investigates questions such as:

- Which genres have higher average viewer engagement?
- Which episode characteristics are associated with higher drop-off?
- How do pacing, hook strength, and cognitive load relate to watch percentage?
- Which content categories show higher retention risk?
- What actionable insights can support content strategy and viewer experience improvements?

## Project Objectives

- Perform structured Exploratory Data Analysis.
- Identify viewing engagement and drop-off patterns.
- Analyze genre-wise and episode-wise performance.
- Examine relationships between content characteristics and viewer engagement.
- Develop an analytical engagement score.
- Categorize episodes based on retention risk.
- Generate business insights and data-driven recommendations.

## Dataset Information

- Dataset: `OTT_Viewer_DropOff_Retention_Risk.csv`
- Total Records: 33,200
- Total Features: 22
- Data Type: Synthetic OTT viewing dataset

### Key Features

| Feature | Description |
|---|---|
| show_id | Unique content identifier |
| title | Show or episode title |
| genre | Content genre |
| episode_duration_min | Episode duration |
| pacing_score | Episode pacing indicator |
| hook_strength | Strength of opening hook |
| dialogue_density | Dialogue intensity |
| visual_intensity | Visual stimulation level |
| avg_watch_percentage | Average percentage watched |
| pause_count | Number of pauses |
| rewind_count | Number of rewinds |
| skip_intro | Intro skipping indicator |
| cognitive_load | Cognitive complexity indicator |
| drop_off | Episode drop-off indicator |
| drop_off_probability | Estimated drop-off probability |
| retention_risk | Retention risk category |

## Technology Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

## Project Workflow

1. Data Loading and Inspection
2. Data Cleaning and Quality Checks
3. Exploratory Data Analysis
4. Univariate and Numerical Analysis
5. Genre-wise Engagement Analysis
6. Episode Drop-off Analysis
7. Engagement Score Analysis
8. Retention Risk Analysis
9. Hook Strength and Pacing Analysis
10. Cognitive Load Analysis
11. Season-wise Performance Analysis
12. Correlation Analysis
13. Business Insights and Recommendations

## Key Analytical Areas

- Viewer engagement distribution
- Genre performance comparison
- Episode drop-off patterns
- Watch percentage analysis
- Content pacing and hook strength
- Cognitive load and attention patterns
- Retention risk distribution
- Correlation between numerical variables

## Business Value

The analysis demonstrates how data analytics can help OTT businesses:

- Understand content engagement patterns.
- Identify episodes associated with higher drop-off.
- Compare genre-level content performance.
- Explore content characteristics linked to viewer attention.
- Support data-informed content optimization strategies.

## Project Limitations

- The dataset is synthetic and does not represent actual Hotstar data.
- No individual viewer identifier is available.
- Individual-level churn prediction cannot be performed using this dataset.
- Correlation does not establish causation.
- Retention risk categories are analytical indicators, not confirmed business outcomes.

## Future Improvements

- Integrate real-world OTT viewing datasets.
- Perform viewer-level behavioral analysis using user identifiers.
- Develop machine learning models for drop-off prediction.
- Build an interactive Streamlit analytics dashboard.
- Implement content recommendation and retention strategies.

## Repository Structure

```text
OTT_Viewer_Engagement_EDA_project/
│
├── data/
│   └── OTT_Viewer_DropOff_Retention_Risk.csv
│
├── notebooks/
│   └── Hotstar_Viewer_Engagement_EDA.ipynb
│
├── outputs/
│   ├── charts/
│   └── reports/
│
├── README.md
└── .gitignore
```

## How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open the project folder

```bash
cd OTT_Viewer_Engagement_EDA_project
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` folder and run the cells.

## Author

**Data Science Portfolio Project**

Developed using Python and data analytics techniques to explore OTT viewer engagement, episode drop-off, and retention risk.
