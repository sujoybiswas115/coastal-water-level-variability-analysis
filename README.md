# Coastal Water Level Variability Analysis (1986–2024)

A Python-based analysis of long-term coastal tidal water level observations to investigate annual variability, extreme high-water events, and seasonal patterns.

## Project Overview

Coastal regions are influenced by tidal processes, storm surges, and other hydrological factors. Understanding long-term water level variability is important for coastal hazard assessment and hydrological research.

This project develops a reproducible Python workflow to process and analyze daily tidal water level observations from 1986 to 2024.

The analysis includes:

- Data preprocessing and quality control
- Statistical analysis of water level observations
- Annual maximum water level analysis
- Extreme high-water event identification
- Seasonal variability assessment
- Scientific visualization

## Objectives

1. Preprocess and clean long-term tidal water level observations.
2. Analyze annual maximum water level variability.
3. Identify extreme high-water events.
4. Investigate seasonal patterns of extreme water levels.
5. Demonstrate a reproducible Python-based hydrological data analysis workflow.

## Dataset Description

The analysis covers the period **1986–2024**.

After preprocessing and removal of incomplete records, **12,694 daily observations** were retained.

| Variable | Description |
|---|---|
| Date | Observation date |
| Daily Max WL (mMSL) | Daily maximum water level |
| Daily Min WL (mMSL) | Daily minimum water level |
| Daily Avg WL (mMSL) | Daily average water level |

> The raw observational dataset is not included in this repository. The repository contains the processed workflow, outputs, figures, and project report.

## Tools and Libraries

- **Python** — analytical environment
- **Pandas** — data processing and manipulation
- **NumPy** — numerical calculations
- **Matplotlib** — scientific visualization

## Methodology Workflow

```text
Raw Water Level Data
        ↓
Data Import
        ↓
Data Cleaning and Preprocessing
        ↓
Date and Time Processing
        ↓
Descriptive Statistical Analysis
        ↓
Annual Maximum Extraction
        ↓
Extreme Event Identification
        ↓
Seasonal Analysis
        ↓
Visualization and Interpretation
