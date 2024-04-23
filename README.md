# MelbCV_R
MelbCV.csv is a subset of Melbourne sidewalk surveillance data. I used the general strategy of exploring a new data set to conduct exploratory analysis, and used statistical descriptions or graphics to answer the following research questions:
1. How many records are there in this data set? How many variables? What is the variable name? Do they make sense? What type is each variable? How many unique values are there for each variable? What value appears most frequently, and how often? Are there any missing values? If so, how often does this happen?
2. Based on the preliminary exploration in 1.1, you know the basic situation of the data set. Next, you need to do the exploration of interest. Through the observation of variables and descriptive statistics, determine whether there are variables in the data set that can be ignored. If so, what are they? One of the variables Weekday_End, how many unique values does it have? Explain the meaning of the value based on the relevant variables of the data set and common sense;
3. Use descriptive statistics (number 5) and graphs (choose appropriate graphs) to describe the characteristics of each crosswalk monitoring data;
4. Use the monitoring point data to draw a scatter matrix plot and observe whether there is any correlation between the monitoring data of each sidewalk. Which variables are correlated?
5. Based on statistical data, answer which times of the day are the peak times for pedestrians at each monitoring point. Do all monitoring points have consistent peak traffic times? If so, which period (s) is it? Which intersection has the largest flow of people? Which intersection has the least amount of people? On what basis is the conclusion drawn? At which monitoring point, at which day and during which period does the maximum flow of people occur?
6. Are there missing values? In which variable(s) does it appear? Can it be ignored? If not, explain the reason and try to impute it. What kind of imputation strategy is more appropriate?
7. Try to establish corresponding statistical models for variables with obvious correlations, and test the models through plotting.

## data

|colname|Meaning|Type|Number of unique values|Mode|
|-|-|-|-|-|
|Date |Date|character|30|All values appear with the same frequency|
|Year |Year|double|1|All values appear with the same frequency, 2012|
|Month |Month|double|1|All values appear with the same frequency, 9|
|Mdate |Day|double|30|All values appear with the same frequency|
|Weekday_End |Indicates weekends or working days, 10 represents working days, 20 represents weekends|double|2|All values appear with the same frequency, 10,20|
|Day |Indicates the day of the week, Sunday is the first day|double|7|1,7|
|Hour |Represents the hour of the day|double|24|All values appear with the same frequency|
|Town_Hall-West|Number of people passing on the sidewalk in Town_Hall-West|double|613|35|
|Collins Place-South|Number of people walking on the sidewalk at Collins Place-South|double|485|10|
|Australia on Collins|Number of pedestrians in Australia on Collins|double|498|16|
|Bourke Street Mall-South|Number of people passing on the sidewalk at Bourke Street Mall-South|double|552|12|
|Bourke Street Mall-North|Number of people passing on the sidewalk at Bourke Street Mall-North|double|548|4|
|Melbourne Central|Number of pedestrians in Melbourne Central|double|598|32|
|Flagstaff Station|Number of people passing on the sidewalk at Flagstaff Station|double|392|10|
|State Library|Number of pedestrians at Flagstaff Station|double|308|24|

<img width="364" alt="image" src="https://github.com/ChelseaLiu0822/MelbCV_R/assets/144384967/def6c855-d260-4227-9861-91085442b6a4">

<img width="364" alt="image" src="https://github.com/ChelseaLiu0822/MelbCV_R/assets/144384967/73aa2928-ed00-44e6-a93a-1346b42b1244">

<img width="364" alt="image" src="https://github.com/ChelseaLiu0822/MelbCV_R/assets/144384967/20e39ab1-b91a-426d-af95-c3fda6d2b598">

<img width="364" alt="image" src="https://github.com/ChelseaLiu0822/MelbCV_R/assets/144384967/1410d443-aa20-40bc-a513-d6d91b725377">
