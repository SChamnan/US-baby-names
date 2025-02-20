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

### Views Breakdown
The top part of the dashboard displays title of the dashboard and its developer's name. There 3 main filters followed by total counts of female babies and male babies.
- Year : displays value of each year from 1910 to 2012 (i.e. 1910, 1920, ...., 2012). This fitler can be used to select a single year or multiple year values depands on user' interests.
- Sex : shows two values option for baby sex as a biological male or biological female.
- Baby Name : list all baby name from the dataset in an alphabetical order (i.e. Addison, Carol, David, Benjamin, ...etc.)
<img width="1375" alt="image" src="https://github.com/user-attachments/assets/25232f29-0274-4de1-b609-21b560117fca" />

The map displays each state in the United States. The map can be used as a filter to filter out data to specific state or scope of states. To filter, select on any state(s) and the dashboard will update.
<img width="1386" alt="image" src="https://github.com/user-attachments/assets/6998ea8c-5993-407b-ab88-e224b2caa48d" />

Example: California state is selected and the dashboard updates the visualization to reflect on the selection. As we can see, the top three most popular names of all time in California are Michael, Robert and Jennifer. Moreover, the bar graph on the right side shows Sophia and Jacob are the most popular names used to name babies in California in 2012.

<img width="1217" alt="image" src="https://github.com/user-attachments/assets/fd0c977e-0d99-4339-b8f5-ac8c91008f82" />

The bottom part of the dashboard displays two line graphs showing how each popular name by sex changes overtime.
For instance, the graph on the right shows that Emma was a popular name in early 2000s and then the trend rose again a decade later. Similarly, the graph on the left side shows there was a spike of baby name David around 1955 and then rose again in the 1960s with 43,055 babies were name David in 1960.
<img width="1387" alt="image" src="https://github.com/user-attachments/assets/51b483f0-82c0-440f-a1c8-a2b26ead6a34" />







