# Smart Meter Data Analysis for Energy Management

## Goal
We will analyze the energy meter data from the CEEW study titled **"What Smart Meters Can Tell Us: Insights on Electricity Supply and Use in Mathura and Bareilly Households"**

**Background:** CEEW team installed nearly 93 smart meters in urban households and collected high-frequency data every 3 minutes from the Mathura and Bareilly districts of Uttar Pradesh. They conducted a preliminary analysis, provided insights into household consumption patterns, and investigated gaps in the quality of supply. They also discussed how power distribution companies can utilize smart meter data for effective service delivery and demand management. 

 - Link to the report: https://www.ceew.in/publications/what-smart-meters-can-tell-us
 - Link to the dataset: https://doi.org/10.7910/DVN/GOCHJH
 
**List of dataset files:**

 - CEEW - Smart meter data Bareilly 2019.tab
 - CEEW - Smart meter data Bareilly 2020.csv
 - CEEW - Smart meter data Bareilly 2021.csv
 - CEEW - Smart meter data Mathura 2019.csv
 - CEEW - Smart meter data Mathura 2020.csv 
 - CEEW - Smart meter data Mathura 2021.tab

## Project Outline
1. **Data Collection**: Collected smart meter data from two locations (Bareilly and Mathura), measuring electricity consumption at regular intervals.
2. **Data Preprocessing**: Performed cleaning and preprocessing of the dataset, extracting time-based features (e.g., hourly, daily, monthly consumption).
3. **Exploratory Data Analysis (EDA)**: 
   - Visualized energy usage trends.
   - Identified peak consumption periods, seasonal patterns, and outliers.
   - Conducted a comparative analysis of consumption across locations.
4. **Energy Load Profiling**: Created load profiles for different time periods to better understand consumption behavior.
5. **Visualization**: Developed clear and interactive visualizations to highlight energy patterns and potential areas for optimization.

## Methods
- Data cleaning and preprocessing to handle missing values and extract features.
- Time-based aggregation and analysis of energy consumption data.
- Comparative analysis across locations (Bareilly vs Mathura).
- Visualization of energy usage patterns and identification of peak consumption periods.
- Load profiling for categorizing energy behavior.

## Libraries Used
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical operations.
- **Matplotlib** & **Seaborn**: For data visualization and plotting.
- **Scikit-learn**: For clustering and machine learning tasks.
- **DateTime**: For handling time-based features.
- **Jupyter Notebook**: For interactive code execution and analysis.

