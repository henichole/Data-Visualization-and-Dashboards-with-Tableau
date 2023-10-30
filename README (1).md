

# Final-Project-Tableau

## Project/Goals
The objective of this project is to analyze and present trends and correlations within tuberculosis incident, prevalence, and mortality data globally from 1990 to 2013. The aim is to conduct data cleaning, exploratory data analysis (EDA), and create comprehensive visualizations using Tableau. The primary goal is to communicate these findings to the general public to raise awareness and engage potential stakeholders in formulating solutions.

## Process
1. Initially, I pulled the dataset into Jupyter Lab to identify and rectify missing or null data. I also corrected country names with special symbols that were inaccurately represented in the dataset.
2. Considering the dataset's size (approximately 50 columns), I streamlined the data by removing estimations of high and low bounds, opting to retain actual averages. Additionally, I eliminated country codes, focusing solely on countries and regions, reducing the dataset to 20 columns.
3. I noted a lack of data regarding HIV patients with tuberculosis in several countries, which I kept in mind throughout the analysis.
4. Post data simplification, I saved the refined dataset as a new Excel file and imported it into Tableau.
5. Utilized Tableau for data visualization, incorporating maps, date and time elements, analytical visuals (Forecasting, Clustering), and 'Show Me' tables.
6. Observed and analyzed patterns, trends, outliers, etc.
7. Identified significant insights and commenced dashboard creation.
8. Constructed a narrative through the dashboards for presentation.

## Results
1. Trends in Tuberculosis Incidence, Prevalence, and Mortality Rates
Answer: Over the analyzed period:
Incidence dropped from 130 to 110 per 100,000 population.
Prevalence decreased from 220 to 140 per 100,000 population.
Mortality reduced from 31 to 20 per 100,000 population globally.

2. What is the region with the Highest Mortality Rate (with and without HIV factor)
Answer: AFRINIC region exhibits the highest mortality rate.

3. Correlation between Incidence and Mortality
Answer: A positive correlation exists between incidence and mortality rates.

## Challenges 
1. HIV Data Null Values: The challenge arose from numerous null values in the HIV data, impacting the accurate assessment of the correlation between HIV and tuberculosis.

2. Data Integrity for Deriving Rates: The presence of null values in methods used to derive incidence, prevalence, and mortality rates hindered determining regions or countries with the most effective detection practices. Retaining these null values highlights gaps in tuberculosis detection methodologies.

## Future Goals
1. Plan to utilize APIs for gathering current data beyond 2013, assessing any changes in the scenario.

2. Investigate the spike in incidence and mortality observed between 1998-2003 for potential events or factors influencing these trends.
