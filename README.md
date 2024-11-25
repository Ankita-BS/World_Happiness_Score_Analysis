# World_Happiness_Score_Analysis
This is a data analysis project of world happiness which is rooted in understanding the well-being and quality of life across different nations. Several factors influence happiness, including social support, health, income, freedom, trust in government, and perceptions of corruption. It is interesting to explore relationships between these factors and happiness levels, aiming to derive insights that could guide policies, interventions, and investments.

### Project Summary
The project involved sourcing an open data and defining business questions and objective.
Data integration, cleaning and transformation was done followed by data exploration, data wrangling and consistency checks.
The analysis involved graphical visualization in python to derive actionable insights. Regression analysis and Cluster analysis was performed. Did time series analysis to explore the happiness trend over the years and finally created data dashboards for visual analysis in Tableau.

### Project Objective
The objective of this project is to quantify and compare Happiness Levels Globally, analyse contributing factors and identify key trends and patterns and to explore how GDP  of a country relate to happiness.

### Hypothesis 
If the GDP per capita of a country increases, then Happiness score also increases.

### Key Questions
1.	Which countries have the highest and lowest happiness scores?
2.	How does the average happiness score vary across different regions?
3.	What is the average happiness score across all countries?
4.	Is there a trend in global happiness over recent years? Are happiness levels generally increasing or decreasing?
5.	Are there countries where happiness scores have consistently improved or declined over time?
6.	What factors correlate most strongly with happiness scores globally?
7.	How does GDP per capita relate to happiness? Are wealthier countries generally happier?
8.	Do countries with higher social support programs have higher happiness scores?
9.	What is the relationship between life expectancy and happiness scores?
10.	Are there specific countries where high life expectancy does not correspond to high happiness (or vice versa)?
11.	Is there a connection between freedom_to_make_life_choices and happiness?
12.	Do people in countries with higher corruption levels report lower happiness?
13.	How have happiness scores changed year-over-year for specific countries or regions?
14.	How does the distribution of happiness scores look? (e.g., skewed, normal, etc.)
15.	Are there common traits among the least happy countries?
16.	Is the relationship between GDP per capita and happiness score linear?
  
### Folders
Description of folder contents are as follows:
- 02 Data: Includes two subfolders
  - 'Original Data': Original datasets.
  - 'Prepared Data': Cleaned data ready for analysis.
- 03 Scripts: Python code for the analysis, executed using Jupyter notebooks.
- 04 Analysis: Contains the 'Visualizations' subfolder with all visualizations used for exploratory analysis and explaining insights.
- 05 Sent to Client: Final presentation.

### Code Overview
Code was written in Python and executed in Jupyter notebooks.

### Utilizes the following libraries:
- Pandas: For data manipulation and analysis
- NumPy: For numerical operations and array handling
- OS: For interacting with the operating system, including file and directory operations
- Matplotlib.pyplot: For creating static, interactive, and animated visualizations
- Seaborn: For statistical data visualization and creating informative, attractive graphics
- Scipy: For scientific and technical computing, including advanced mathematical functions
- Folium, Json: For geospatial analysis
- sklearn: For Linear Regression
- statsmodels: To handle statistical models 

### Data Source
https://www.kaggle.com/datasets/sazidthe1/global-happiness-scores-and-factors 
This dataset provides valuable insights in understanding the dynamics of happiness and well-being worldwide. This dataset includes key metrics related to global happiness across all the regions for 9 years from 2015-2023. There are 9 different files, one for each year, all of which are concatenated for the analysis.
The project includes 2 Json shapefiles for countries and continents.

### Visualizations
View visualizations here: <a href="https://public.tableau.com/app/profile/ankita.bs/viz/WorldHappinessAnalysis_17324863339870/Story1">
                    <button>  Visualizations on Tableau Public</button>
                    </a> 
The visualization contains only few relevant final results.
