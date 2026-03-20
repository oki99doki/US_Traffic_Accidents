# US_Traffic_Accidents

## Goal
The Goal is to perform comprehensive data analysis on real-world traffic accident data. This includes:

- Data cleaning
- Exploratory data analysis (EDA)
- Statistical analysis
- Data visualization
- Deriving business insights.

## Task
Analyze the US Accidents dataset to identify patterns, trends, and factors contributing to accidents. Based on a comprehensive analysis, there will be three data-driven insights provided that the DOT could utilize to reduce traffic accidents and improve road safety.

## Resources
Here are some resources including a link to the US accidents dataset.

- Dataset: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents
- Template Github Repository: https://github.com/learn-co-curriculum/DS_Capstone_Template#
- Pandas: https://pandas.pydata.org/docs/
- Numpy: https://numpy.org/doc/stable/
- Matplotlib: https://matplotlib.org/stable/contents.html
- Seaborn: https://seaborn.pydata.org/
- SciPy: https://docs.scipy.org/doc/scipy/
- Statsmodels: https://www.statsmodels.org/stable/index.html
- Dashboarding Tool: Tableau
- FHSA data: https://safety.fhwa.dot.gov/
- NHTSA: https://www.nhtsa.gov/research-data

## Potential Areas of Analysis

### Spatial and Temporal Patterns (SELECT)
Consider examining when and where accidents most frequently occur. One might explore patterns by time of day, day of week, season, and geographic location. This type of analysis could potentially reveal critical hotspots and time periods requiring intervention.

- At what times during the day do most accidents happen?
- Are there differences between weekdays and weekends?
- Which states or cities have most accidents?
- Are there seasonal patterns (winter vs. summer)?
  
- [ ] H1: Accidents occur more frequently during rush hours (7-9 am and 4-6 pm).
- [ ] H2: There are more accidents during weekdays (Mo-Fr) compared to weekends (Sa/Su).
- [ ] States with larger populations have significantly more accidents?

### Environmental Factors (SELECT)
One could investigate how weather conditions correlate with accident rates. Consider analyzing how visibility, precipitation, temperature, and other environmental variables might affect driver behavior and road conditions.

- Does bad weather have an impact on frequency and severity of accidents?
- How does visibility impact accidents?
- Are there more accidents during rain / snow / fog?
- Does temperature have an influence?
  
- [ ] H1: Poor visibility leads to higher accident severity.
- [ ] H2: During rain and snow there are more accidents.
- [ ] H3: Extreme temperatures (very cold/ hot) increase accident risk,
- [ ] H4: Weather conditions have a sinificant impact on severity.

### Infrastructure Considerations (SELECT)
One possible avenue is to identify specific road features associated with accident severity. This might include road design, signage, lighting, or other infrastructural elements that could contribute to or mitigate accident risk.

- Which road attributes are connected with most severe accidents?
- Do traffic signals have an influence on accident frequency?
- Are accidents more common at intersections, traffic lights, construction etc.?
- Does lighting (day/night) have an effect?

- [ ] H1: Accidents at intersections (junctions) are more common.
- [ ] H2: Lacking or poor lighting increases severity.
- [ ] H3: Traffic signals decrease the severity of accidents.
- [ ] H4: Construction increases accident risk.
- [ ] H5: Night conditions lead to higher severity.

### Urban vs. Rural Comparison (DO NOT SELECT)
One can compare accident patterns between urban and rural settings. These different environments likely present distinct challenges and risk factors that might require tailored safety approaches.
- 

## Problem Solving Process

To successfully complete this project, follow the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology:

### 1. Business Understanding
Define the problem clearly and identify key questions that your analysis should answer. Determine how success will be measured and what insights would be valuable to stakeholders.

### 2. Data Understanding
Explore the US Accidents dataset to understand its structure, variables, scope, and limitations. Identify potential issues with the data and assess its suitability for addressing the business problem.

### 3. Data Preparation
Clean and preprocess the data, handling missing values, outliers, and duplicates. Create derived features that might provide additional insights (e.g., time of day categories, weather condition groupings).

### 4. Analysis/Statistical Analysis
(Instead of Modeling in traditional CRISP-DM) Apply appropriate statistical methods to identify patterns, correlations, and significant factors. Test hypotheses about accident causes and contributing factors.

### 5. Evaluation
Interpret your findings in the context of the business problem. Assess whether your analysis provides actionable insights and addresses the key questions identified in the business understanding phase.

### 6. Deployment/Communication
(Dashboard + Notebook) Create an interactive dashboard for stakeholders to explore your findings. Develop a well-documented Jupyter notebook that explains your process and conclusions. Prepare a presentation that effectively communicates your insights and recommendations.

Following this standardized process ensures a methodical approach to your analysis, helps maintain focus on business objectives, and results in a comprehensive solution that addresses all aspects of the problem.


## Jupyter Notebook Sections

### Overview
Short project description. Your bottom line up front (BLUF) insights.

Task: Analyze the US Accidents dataset to identify patterns, trends, and factors contributing to accidents. Based on your comprehensive analysis, you'll provide three data-driven insights that the DOT could utilize to reduce traffic accidents and improve road safety.

### Business Understanding
This explains why the project matters in the real world.

Include:

- Business scenario (traffic safety)
- Project motivation
- Analytical questions
- Stakeholders
- Expected benefits

Examples of content:

#### Problem

Traffic accidents cause significant injuries, fatalities, and economic losses each year.

#### Questions

- Are accidents more severe during nighttime?
- Does precipitation increase accident severity?
- Which road features correlate with higher accident risk?

#### Stakeholders

- Transportation departments
- Urban planners
- Traffic safety agencies

### Data Understanding
This section explains what data is available have and what it contains. Include:

Tasks:

- [X] Load dataset
- [X] Show dataset size (df.shape)
- [X] Inspect structure (df.info())
- [X] Describe variables (df.describe())
- [ ] Document variables and meaning
- [X] Identify categorical vs numerical columns
- [X] Explore missing values
- [X] Initial visualizations

Example topics:

Number of rows and columns
Types of variables (numeric, categorical, boolean)
Key columns such as Severity, Temperature, Visibility
Missing data patterns

### Data Preparation
This section explains how the data is cleaned and transformed before analysis.

Tasks:

- [ ] Handling missing values
- [ ] Filtering invalid values
- [ ] Removing outliers
- [ ] Converting data types (e.g., datetime)
- [ ] Creating new variables
- [ ] Feature engineering
- [ ] Subsetting columns
- [ ] Encoding categorical variables (if used)

Examples:

Convert Start_Time to datetime
Create Hour or DayOfWeek
Remove unrealistic weather values
Filter extreme wind speeds
Example code actions you performed.

### Analysis
This is where the actual findings are presented.

Include:

- [ ] Visualizations
- [ ] Statistical summaries
- [ ] Relationships between variables
- [ ] Answers to analytical questions

Examples:

Accident severity vs precipitation
Day vs night accident comparison
Weather conditions and accident frequency
Geographic distribution of accidents
Correlations between variables
Explain what the plots mean.

### Evaluation

#### Business Insight/Recommendation 1¶
xxx

#### Business Insight/Recommendation 2¶
xxx

#### Business Insight/Recommendation 3

#### Tableau Dashboard link¶
Link here ...

### Conclusions and Next Steps
xxx


