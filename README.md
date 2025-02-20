# US-baby-names
This Tableau dashboard analyzes over 12 million records of baby names in the United States to explore some interesting findings. To access the live dashboard on Tableau platform, visit https://public.tableau.com/app/profile/chamnan.suon/viz/BabyNamesinUnitedStates/Dashboard2.

## Dataset and Data Description

Total of 12,457,703 records are obtained from Social Security Administration - https://www.ssa.gov/oact/babynames/limits.html. There are 5 fields in this dataset and each field is described as follow: 
- `state` (varchar) each state in United States.
- `gender` (boolean) biological sex at birth (F = female, M = male).
- `top_name` (varchar) the most used male or female name in a given state at a given year (For example, in 1910 the most used female name in Alaska is Mary with the records of 14 instances).
- `occurence` (bigint) aggregated numbers of each name in each state per year.
- `year` (date) year in which baby was born

Upon reveiwing and analyzing, this dataset is already clean and make ready to use for analysis by the source. No further clearning is needed.

## Data Visualization and Filters
The visualization of US Baby Names is published on Tableau Public: https://public.tableau.com/app/profile/chamnan.suon/viz/BabyNamesinUnitedStates/Dashboard2.

Below is an overview of the dashboard on Tableau

<img width="1056" alt="image" src="https://github.com/user-attachments/assets/327be642-1ef9-47d0-9f54-a6728bbaa017" />


At the top of the dashboard, there are three main filters:
- Year : displays value of each year from 1910 to 2012 (i.e. 1910, 1920, ...., 2012). This fitler can be used to select a single year or multiple year values depands on user' interests.
- Sex : shows two values option for baby sex as a biological male or biological female.
- Baby Name : list all baby name from the dataset in an alphabetical order (i.e. Addison, Carol, David, Benjamin, ...etc.)
<img width="1385" alt="image" src="https://github.com/user-attachments/assets/699c7070-89cc-4fa0-a270-0e91594fb2ec" />

At the bottom of the dashboard, there are two additional filters used to observe trends of each baby name throughout the years.
<img width="1305" alt="image" src="https://github.com/user-attachments/assets/7c83f6d5-6fc3-4e72-af09-5bc0001159d1" />

### Views Breakdown
The top part of the dashboard displays title of the dashboard and its developer's name. There 3 main filters followed by total counts of female babies and male babies.
<img width="1375" alt="image" src="https://github.com/user-attachments/assets/25232f29-0274-4de1-b609-21b560117fca" />

The map displays each state in the United States. The map can be used as a filter to filter out data to specific state or scope of states. To filter, select on any state(s) and the dashboard will update.
<img width="1386" alt="image" src="https://github.com/user-attachments/assets/6998ea8c-5993-407b-ab88-e224b2caa48d" />

Example: California state is selected and the dashboard updates the visualization to reflect on the selection. As we can see, the top three most popular names of all time in California are Michael, Robert and Jennifer. Moreover, the bar graph on the right side shows Sophia and Jacob are the most popular names used to name babies in California in 2012.

<img width="1217" alt="image" src="https://github.com/user-attachments/assets/fd0c977e-0d99-4339-b8f5-ac8c91008f82" />







