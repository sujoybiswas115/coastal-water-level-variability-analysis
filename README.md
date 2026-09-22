\# Coastal Water Level Variability Analysis (1986–2024)



A Python-based analysis of long-term coastal tidal water level observations to investigate annual variability, extreme high-water events, and seasonal patterns.



\---



\## Project Overview



Coastal regions are highly influenced by tidal processes, storm surges, and other hydrological factors. Understanding long-term water level variability is important for coastal hazard assessment and research.



This project develops a reproducible Python workflow to process and analyze daily tidal water level observations from 1986 to 2024.



The analysis focuses on:



\- Data preprocessing and quality control

\- Statistical analysis of water level observations

\- Annual maximum water level variability

\- Extreme high-water event identification

\- Seasonal variation analysis

\- Scientific visualization



\---



\## Objectives



The main objectives of this project are:



1\. To preprocess and clean long-term tidal water level data.

2\. To analyze annual maximum water level variability.

3\. To identify extreme high-water level events.

4\. To investigate seasonal patterns of extreme water levels.

5\. To develop a reproducible Python-based hydrological data analysis workflow.



\---



\## Dataset Description



The dataset contains daily tidal water level observations covering:



\*\*Period:\*\* 1986–2024



After preprocessing and removal of incomplete records:



\*\*Total observations analyzed: 12,694 daily records\*\*



\### Variables



| Variable | Description |

|----------|-------------|

| Date | Observation date |

| Daily Max WL (mMSL) | Daily maximum water level |

| Daily Min WL (mMSL) | Daily minimum water level |

| Daily Avg WL (mMSL) | Daily average water level |



\---



\## Tools and Libraries



The analysis was performed using:



\- Python

\- Pandas

\- NumPy

\- Matplotlib



\### Purpose



\- Pandas → Data processing and manipulation

\- NumPy → Numerical calculations

\- Matplotlib → Scientific visualization



\---



\## Methodology Workflow



\---



\## Key Results



\### Annual Maximum Water Level Analysis



Annual maximum water levels were extracted from daily observations.



A linear trend analysis showed:



\- Annual increasing tendency:



\*\*0.00517 m/year\*\*



\- Total change during study period:



\*\*Approximately 0.207 m\*\*



\- Linear trend performance:



\*\*R² ≈ 0.033\*\*



The low R² indicates considerable year-to-year variability in extreme water levels.



\---



\## Extreme High-Water Events



Extreme events were identified using:



Results:



\- Total extreme events identified: \*\*12\*\*

\- Highest recorded event:



\*\*27 May 2024\*\*



Maximum water level:



\*\*2.950 mMSL\*\*



\---



\## Seasonal Pattern



Monthly analysis showed:



\- Highest extreme water level during \*\*May\*\*

\- Additional high values during:

&#x20; - August

&#x20; - October



This indicates that extreme water level conditions are seasonally variable.



\---



\## Project Structure



\---



\## Visual Outputs



\### Annual Maximum Water Level Trend



Shows long-term variability of annual maximum water levels.



\### Extreme Event Timeline



Shows temporal distribution of extreme events exceeding 2.5 mMSL.



\### Monthly Extreme Pattern



Shows seasonal variation of maximum observed water levels.



\---



\## Applications



This workflow can support:



\- Coastal hazard assessment

\- Hydrological time-series analysis

\- Extreme event characterization

\- Research-oriented data processing

\- Future statistical modelling studies



\---



\## Future Improvements



Possible extensions:



\- GEV/GPD extreme value modelling

\- Cyclone event comparison

\- Sea-level trend analysis

\- Machine learning-based prediction

\- GIS and remote sensing integration



\---



\## Author



Academic portfolio project demonstrating Python-based coastal hydrological data analysis skills.



