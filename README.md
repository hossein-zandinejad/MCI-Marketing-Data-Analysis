# MCI Marketing Data Analysis
Hamrah Aval Marketing Data Analysis Project

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
  - [Clone the Repository](#clone-the-repository)
  - [Dependencies](#dependencies)
- [Project Details](#project-details)
  - [Data Loading and Preprocessing](#data-loading-and-preprocessing)
  - [General Analysis](#general-analysis)
  - [Relationship Between Indicators](#relationship-between-indicators)
  - [Analyze Traffic Consumption](#analyze-traffic-consumption)
  - [Trend Analysis for Message-Related Metrics](#trend-analysis-for-message-related-metrics)
  - [Trend Analysis for Channel-Related Metrics](#trend-analysis-for-channel-related-metrics)
  - [Goal-Oriented Analysis](#goal-oriented-analysis)
  - [Statistical Analysis: Rolling Averages](#statistical-analysis-rolling-averages)
  - [Statistical Analysis: Trend Analysis](#statistical-analysis-trend-analysis)
  - [Statistical Analysis: Hypothesis Testing](#statistical-analysis-hypothesis-testing)
  - [Summary and Reporting](#summary-and-reporting)
  - [Additional Visualizations](#additional-visualizations)
- [Conclusion](#conclusion)

## Introduction
This repository contains the code and documentation for the analysis of user and message metrics. The project focuses on gaining insights into user activity and messaging behavior over time, using data analysis techniques, data visualization, and statistical analysis.

## Project Overview
The project involves various steps and analyses, including data loading and preprocessing, general analysis, trend analysis, goal-oriented assessments, and statistical testing. It aims to provide a comprehensive understanding of the dataset's dynamics and relationships between different metrics.

## Getting Started

### Clone the Repository
To clone this repository to your local machine, use the following command:

```bash
git clone https://github.com/hossein-zandinejad/MCI-Marketing-Data-Analysis.git
```
## Dependencies

Before running the project code, make sure you have the required dependencies installed. You can install them using pip:

```bash
pip install pandas numpy plotly statsmodels scipy tabulate
```

## Project Details

### Data Loading and Preprocessing

Load the dataset from an Excel file.

Rename columns for clarity and easier access.

### General Analysis

Create line plots to visualize trends in key metrics, such as Active Users, New Users, and Message Count.

### Relationship Between Indicators

Generate a heatmap to visualize the correlation matrix between various indicators.

### Analyze Traffic Consumption

Create line plots to analyze the trend in Average Traffic per User.

### Trend Analysis for Message-Related Metrics

Create line plots to analyze trends in Message Count, Message Forwards, and Message Views.

### Trend Analysis for Channel-Related Metrics

Create line plots to analyze trends in New Channels, Channel Subscriptions, and Effective Channel Users.

### Goal-Oriented Analysis

Set a goal to increase traffic by a specified percentage.

Calculate the necessary increase in traffic.

Estimate the impact of changes in metrics on traffic consumption.

### Statistical Analysis: Rolling Averages

Calculate rolling averages for Message Count and Message Forwards to identify longer-term trends.

### Statistical Analysis: Trend Analysis

Perform linear regression to analyze trends in Message Count and Message Forwards.

### Statistical Analysis: Hypothesis Testing

Compare the means of Message Count and Message Forwards using a t-test.

### Summary and Reporting
Create a structured table to summarize key results.

Display the summary of the trend analysis.

### Additional Visualizations

Create line plots to visualize the 7-day rolling averages of Message Count and Message Forwards.

