# Landscape of U.S. Health

## Project Summary

This project focuses on analyzing health indicators amongst the U.S. population, such as PhysicalHealth, MentalHealth, BMI, and SleepHours, to uncover patterns and correlations that can inform public health interventions. The analysis explores potential relationships among these measures, examines geographic variation across states, and investigates whether clustering approaches can identify distinct health profiles. Although the linked storyboard showcases the primary findings, it does not include every exploratory step or data transformation conducted along the way.

## Key Questions

1. **How do poor physical and mental health days correlate across respondents?**
2. **Are there notable regional differences in average BMI by state?**
3. **Do BMI and poor PhysicalHealth alone suffice for meaningful clustering, or are additional variables needed?**
4. **What other demographic or behavioral aspects might influence these health measures?**

## Data & Tools

### Data Sources

- **Cleaned_Heart_Health_Data.csv**
  - Derived from the Centers for Disease Control and Prevention’s (CDC) Behavioral Risk Factor Surveillance System (BRFSS).
  - Contains self-reported information on physical and mental health days, BMI, and related lifestyle indicators.
  
- **Shapefile for U.S. State Boundaries**
  - Used to create the choropleth map.
  - Sourced from publicly available GIS repository (US States GeoJSON).

### Tools Used

- **Jupyter Notebook (Python, Pandas, NumPy)**
  - Employed for data cleaning, preliminary exploration, and any preprocessing steps prior to visualization.
  
- **Tableau Desktop**
  - Used for data visualization and creating the final storyboard.
  
- **GIS Software (optional)**
  - Utilized if verifying or modifying shapefile properties for mapping purposes.

## Tableau Storyboard

A curated set of visualizations is available on [Tableau Public](https://public.tableau.com/views/LandscapeofU_S_Health/Storyboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link). These views summarize the primary analysis and conclusions. Background steps—such as detailed data preparation, additional exploratory plots, and iterative testing—are omitted from the storyboard for clarity.

## Folder Structure

Within this repository, you will find the following folders to maintain logical organization:

1. **01 Project Management**
   - Contains the project brief and related documentation
   
2. **02 Data**
   - Includes two subfolders:
  'Original Data': Original datasets.
  'Prepared Data': Cleaned data ready for analysis.
   
3. **03 Scripts**
   - Holds Jupyter notebooks containing Python scripts for data cleaning, exploration, analyses, and visualizations.
   
4. **04 Analysis : Visualizations**
   - Contains the choropleth map.
   
5. **05 Storyboard**
   - Includes file with link to Tableau storyboard.

## Disclaimer

- The dataset originates from the CDC’s BRFSS (publicly available), which relies on self-reported health data and may be subject to bias or inaccuracies.
- Geographic shapefile data are likewise publicly sourced and used exclusively for illustrative mapping.
- This project is for educational and exploratory purposes, and the findings herein should not be construed as definitive public health guidance.
