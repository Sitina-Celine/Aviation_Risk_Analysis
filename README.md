# Aviation Risk analysis
 
 ## Project Summary
 This project analyzes Aviation incidents to uncover trends,identify risk factors and recommend safer aircraft choices.It is based on realife incident data and focuses on factors such as aircraft make,weather,flight phase and location.

 ## Business understanding
 Business Problem: The company is expanding into commercial and private aviation but lacks insight into the safety risks of aircraft types. The goal is to determine which aircraft types pose the lowest risk, helping the company make informed acquisition decisions.

**Key Business Questions:**
* Which aircraft makes and categories have historically low incident and fatality rates?
* What environmental or mechanical factors contribute to higher injury severity?
* What trends in incident data can inform low-risk investment decisions?


## Business problem
 A new aviation business needs to choose low-risk aircraft models for its fleet.The goal is to identify which aircraft categories are involved in most  and least severe incidents and determine if weather,location or flight phase impact safety.


## Data understanding
 Source: National Transportation Safety Board (NTSB)
Data Range: 1962 to 2023
File: Civil aviation accident and incident data from the United States and international waters

**Preparation Steps**:

* Dropped irrelevant columns and records with excessive missing values
* Cleaned column names and standardized formatting
* Imputed missing values using domain logic and statistical methods
* Extracted new features (e.g., year, month) for temporal analysis

## Environment and Dependencies
 * Python
 * Tableau
 * Jupiter-Notebook
 * Libraries used:
   * Pandas
   * Matplotlib
   * Seaborn
   * numpy
 
## Visualizations
The project includes multiple visualizations for data exploration and insight communication. Three primary visuals supporting the final recommendations are:
* Fatal Injuries by Aircraft Make
   Identifies which aircraft manufacturers are associated with the highest and lowest fatality rates.
* Serious Injuries by Weather Conditions
   Analyzes how weather impacts incident severity.
* Injury Severity by Aircraft Category
   Compares incident outcomes across various types of aircraft (e.g., airplane, helicopter, balloon).

## Reccomendations
* Focus on aircraft makes with low incident and fatal injury rates to minimize risk.
* Avoid operations in regions or seasons with adverse weather conditions that correlate with higher injury severity.
* Limit initial operations to aircraft categories with consistently low-risk profiles, such as single-engine fixed-wing aircraft.

### To run this project
To reproduce the analysis:
1. Cone the repository.
2. Open student.ipynb in Jupyter Notebook
3. Install required libraries; Pandas,matplotlib

## Interactive dashboard
View the Tableau dashboard here:
Link to Dashboard:
[
](https://public.tableau.com/app/profile/celine.sitinna/viz/aircraftanalysis/aircraftdashboard?publish=yes)


### author:
Celine Sitina.
GitHub:https://github.com/Sitina-Celine/Aviation_Risk_Analysis

## conclusion

This project applies real-world aviation data to develop business intelligence insights for investment decision-making. Through data cleaning, exploratory analysis, visualization, and presentation, the project identifies concrete recommendations to support a data-driven entry into the aviation sector.


 