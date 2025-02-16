# US-baby-names
The Tableau dashboard below is developed is analyze trends of baby names in the United States in the course of over 100 years ago, from 1910 to 2012. For an interactive experience in using this dashboard, please visit https://public.tableau.com/app/profile/chamnan.suon/viz/BabyNamesinUnitedStates/Dashboard2.

## Data Preparation
### Data and Fields Description
Dataset is obtained from Social Security Administration - https://www.ssa.gov/oact/babynames/limits.html with the total of 10,506 records of rows and 5 columns.
- `state` (varchar) each state in United States.
- `gender` (boolean) biological sex at birth (F = female, M = male).
- `top_name` (varchar) the most used male or female name in a given state at a given year (For example, in 1910 the most used female name in Alaska is Mary with the records of 14 instances).
- `occurence` (bigint) total number of instances of each top name being used in each state, each sex category and each year.
- `year` (date) each year of each top name.

### Data Clearning
Data is already clean and make ready to use for analysis by the source. No further clearning is needed.

## Visualization and Data Manipulation
The visualization of this data is designed and developed on Tableau Public, a free online platform for exploring, sharing, and building data visualizations.
Three fields are used as filters to filter and manipulate result on dashboard.
- `year` used as a filter to include or exclude year(s) of interest in the visualization. For instance, in Figure. 1 below, all years are included in the year filter resulting in congested display of the dashboard. In Figure 2, however,

Figure 1
![image](https://github.com/user-attachments/assets/48bd6c90-ec2b-432f-8764-b6c370fe0a6b)

Figure 2
![image](https://github.com/user-attachments/assets/55497a3d-a0f3-4b5f-9da8-0387c5ec7954)
