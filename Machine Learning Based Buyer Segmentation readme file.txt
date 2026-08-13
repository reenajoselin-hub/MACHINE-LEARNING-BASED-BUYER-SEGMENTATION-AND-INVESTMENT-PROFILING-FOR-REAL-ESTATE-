# Machine Learning Based Buyer Segmentation and Investment Profiling for Real Estate Market Intelligence

## Project Overview

This internship project focuses on analysing real estate buyer data to identify meaningful buyer patterns, segment buyers using clustering techniques, and generate insights for real estate market intelligence and investment profiling.

The project combines data analysis, machine learning-based buyer segmentation, and Tableau business intelligence to study buyer demographics, geographic distribution, buyer purpose, client type, satisfaction, referral channels, and financing behaviour.

An interactive Tableau dashboard was developed to present the analytical findings and enable users to explore different buyer segments through interactive filters.

## Objectives

The primary objectives of this project are:

- To analyse the characteristics and behaviour of real estate buyers.
- To identify geographic and regional patterns in the buyer population.
- To analyse buyer purpose and client-type patterns.
- To examine buyer satisfaction levels.
- To analyse referral channels and loan behaviour.
- To segment buyers using clustering techniques.
- To develop an interactive Tableau dashboard for real estate market intelligence.
- To generate insights that can support buyer targeting and investment profiling.

## Dataset

The project uses a real estate buyer dataset containing 2,000 buyer records.

The major variables considered in the analysis include:

- Client Id
- Age
- Gender
- Country
- Region
- Buyer Purpose
- Client Type
- Satisfaction Score
- Satisfaction Category
- Referral Channel
- Loan Status
- Cluster

These variables were selected to analyse demographic, geographic, behavioural, satisfaction, acquisition, and financing characteristics of real estate buyers.

## Methodology

The project follows a structured analytical workflow:

1. Data Collection
2. Data Preparation
3. Exploratory Data Analysis
4. Buyer Behaviour Analysis
5. Buyer Segmentation
6. Tableau Visualization
7. Dashboard Development
8. Business Insights and Interpretation

### Data Preparation

The dataset was examined and prepared for analysis. Numerical and categorical variables were used according to their analytical purpose.

### Exploratory Data Analysis

The buyer dataset was analysed to understand:

- Overall buyer distribution
- Geographic patterns
- Buyer purpose
- Client type
- Satisfaction levels
- Referral channels
- Loan behaviour

### Buyer Segmentation

Clustering was applied to segment buyers based on Age and Satisfaction Score.

The final segmentation produced four buyer clusters.

### Tableau Dashboard

The analytical results were integrated into an interactive Tableau dashboard containing key performance indicators, charts, geographic analysis, buyer segmentation, and interactive filters.

## Buyer Segmentation

The final clustering model contains four buyer segments:

| Cluster | Number of Buyers |
|----------|-----------------:|
| Cluster 1 | 420 |
| Cluster 2 | 402 |
| Cluster 3 | 621 |
| Cluster 4 | 557 |
| **Total** | **2,000** |

The clusters represent analytical buyer segments based on Age and Satisfaction Score. They are intended for buyer profiling and market intelligence and should not be interpreted as direct financial-risk or investment-value categories.

## Key Dashboard Metrics

The final Tableau dashboard provides the following key indicators:

| Metric | Value |
|--------|------:|
| Total Buyers | 2,000 |
| Highly Satisfied Buyers | 822 |
| Loan Applied | 736 |

## Dashboard Components

The Tableau dashboard includes the following analytical views:

- Total Buyers KPI
- Highly Satisfied Buyers KPI
- Loan Applied KPI
- Geographic Buyer Analysis
- Buyer Satisfaction Analysis
- Referral Channel Analysis
- Loan Behaviour by Region
- Buyer Segmentation Clusters
- Region-wise Buyer Purpose
- Client Type by Buyer Purpose

The dashboard also provides interactive filters for Buyer Purpose, Region, Client Type, and Cluster, allowing users to explore specific buyer groups.

## Key Findings

The analysis provides the following key findings:

- The dataset contains 2,000 distinct real estate buyers.
- 822 buyers are classified as Highly Satisfied.
- 736 buyers have applied for a loan.
- The buyer population can be divided into four analytical clusters based on Age and Satisfaction Score.
- Cluster 3 is the largest segment with 621 buyers, while Cluster 2 is the smallest with 402 buyers.
- Geographic analysis provides insights into the distribution of buyers across regions.
- Buyer Purpose and Client Type provide additional dimensions for understanding buyer behaviour.
- Loan behaviour provides insights into financing patterns among buyers.
- Referral Channel analysis provides information about buyer acquisition sources.

## Business Applications

The analytical framework developed in this project can support real estate organizations in:

- Buyer segmentation
- Customer profiling
- Targeted marketing
- Regional market analysis
- Buyer-purpose analysis
- Customer satisfaction management
- Financing behaviour analysis
- Referral-channel evaluation
- Investment-oriented market intelligence

## Tools and Technologies

The project uses the following tools and technologies:

- Tableau for interactive data visualization and dashboard development
- Machine learning clustering techniques for buyer segmentation
- Microsoft Excel for data handling and supporting analysis
- GitHub for project documentation and version control

## Project Structure

The repository contains the project dataset, Tableau workbook, analytical resources, documentation, and supporting project files.

```text
real-estate-buyer-segmentation/
│
├── README.md
├── data/
├── tableau/
├── report/
├── screenshots/
└── analysis/