# Training Feedback Analysis Project

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dependencies](#dependencies)
3. [Data Preparation](#data-preparation)
4. [Analysis](#analysis)
    - [Sentiment Analysis](#sentiment-analysis)
    - [Topic Modeling](#topic-modeling)
    - [Statistical Analysis](#statistical-analysis)
5. [Visualizations](#visualizations)
6. [LaTeX Report](#latex-report)
7. [Results and Recommendations](#results-and-recommendations)
8. [Future Work](#future-work)
9. [Contributors](#contributors)


## Project Overview

This project is focused on analyzing feedback from participants in a series of training sessions. The analysis includes sentiment analysis, topic modeling, and statistical evaluations, with the goal of providing actionable insights and recommendations to improve future training sessions.



## Dependencies

To run this project, you will need the following Python packages:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `TextBlob`
- `wordcloud`
- `jupyterlab` or `jupyter`

## Data Preparation

1. **Raw Data Collection:** Feedback data from various training sessions is stored in CSV files
2. **Data Cleaning:** The raw data is processed to handle missing values, standardize column names, and prepare text data for analysis.
3. **Data Merging:** All feedback CSV files are merged into a single dataset for comprehensive analysis.

## Analysis

### Sentiment Analysis

- **Objective:** To gauge participant sentiment regarding different aspects of the training sessions.
- **Method:** TextBlob is used to calculate sentiment polarity scores for various feedback categories.
- **Output:** Sentiment scores are averaged and visualized to provide an overview of participant satisfaction.

### Topic Modeling

- **Objective:** To identify common themes and topics in the feedback provided by participants.
- **Method:** Latent Dirichlet Allocation (LDA) is used to discover topics within the feedback data.
- **Output:** Word clouds and topic summaries are generated to highlight the key themes.

### Statistical Analysis

- **Objective:** To evaluate the performance of different training sessions and identify top-performing hospitals.
- **Method:** Statistical measures such as mean, standard deviation, and completion rates are calculated.
- **Output:** Performance scores and visualizations (e.g., overlapping histograms, bar charts) are created to compare session performance.

## Visualizations

The following visualizations are generated during the analysis:

- **Sentiment Analysis Bar Chart:** Displays average sentiment scores across feedback categories.
- **Topic Modeling Word Clouds:** Visualizes the most common words associated with key feedback topics.
- **Overlapping Feedback Distribution:** Compares feedback distributions across multiple sessions.
- **Attendance Distribution Bar Chart:** Shows the average attendance rates across different sessions.

## LaTeX Report

A detailed report is generated using LaTeX, which includes the analysis results, visualizations, and actionable recommendations. The report is structured as follows:

1. **Executive Summary**
2. **Introduction**
3. **Detailed Findings**
   - What Went Well
   - Top Learning Points
   - Suggestions for Improvement
4. **Sentiment Analysis**
5. **Statistical Analysis and Performance Evaluation**
   - Top-Performing Hospitals
   - Feedback and Attendance Analysis
6. **Recommendations**
7. **Conclusion**

## Results and Recommendations

The analysis provides insights into the effectiveness of the training sessions, highlighting areas of strength and opportunities for improvement. Key recommendations include enhancing content quality, refining communication training, and addressing language accessibility.

## Future Work

- **Enhanced NLP Techniques:** Implement more advanced NLP techniques such as sentiment classification using machine learning models.
- **Interactive Dashboards:** Develop interactive dashboards to allow real-time exploration of feedback data.
- **Expanded Data Sources:** Incorporate additional data sources such as post-training surveys or interviews for a more comprehensive analysis.

## Contributors

- **Kartikeya Sharma**
