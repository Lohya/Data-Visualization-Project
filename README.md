                                                         DATA VISUALIZATION

SUMMARY:

COVID-19 is a highly contagious viral disease caused by the novel coronavirus SARSCoV-2. It was first identified in Wuhan, China in December 2019 and has since spread 
rapidly around the world, leading to a global pandemic. In the world as of April 30, 
2023, there were over 444 million confirmed COVID-19 cases, and more than 5.9 
million people died from the disease. Brazilian, Indian, and American reports of cases 
and fatalities have been the greatest. Both on the global economy and public health, 
COVID-19 has had a tremendous impact. In order to stop the virus's spread, many 
nations have put in place measures like lockdowns and social seclusion, which have 
disrupted daily life and business. 

❖ The COVID-19 pandemic has also brought attention to the inequities and disparities 
that still exist, with some groups, such as the elderly, the poor, and those with preexisting diseases, being more susceptible to serious sickness or even death from the 
virus. Development and use of vaccinations, which have been proven to be highly 
effective in reducing serious disease and death, have been part of efforts to battle the 
epidemic. 

❖ The introduction of novel viral types, vaccination reluctance, and restricted access to 
vaccines in some nations continue to be problems. In general, COVID-19 has had a 
significant influence on society and will continue to do so for some time to come in 
terms of public health and policy.

❖ The graphical or pictorial depiction of data and information is known as data 
visualization. It enables users to rapidly and simply evaluate significant amounts of 
complicated data, spot trends, patterns, and linkages, and come to wise conclusions 
based on the knowledge gleaned from the visualized data. Numerous industries, 
including business, science, healthcare, and education, use data visualization. It is used 
in business to manage sales and revenue, monitor and evaluate key performance 
indicators (KPIs), and spot trends and expansion prospects. 

❖ It is employed in science to represent study results, contrast experimental findings, and 
explain intricate concepts to a wider audience. People with little to no programming or 
statistical knowledge can now create visually appealing charts, graphs, and interactive 
dashboards thanks to the advancement of user-friendly data visualization tools. Data 
visualization is now crucial for comprehending and making sense of the enormous 
volumes of data generated every day as a result of the emergence of big data and the 
Internet of Things (IoT).

❖ The COVID-19 data can be displayed using a variety of data visualization approaches, 
such as line charts, bar graphs, heat maps, and geographical maps. These visualizations 
can show COVID-19 cases, deaths, and hospitalizations on a daily or cumulative basis 
by area, age, and gender, among other factors. users can drill down into the data and 
explore various scenarios by using interactive dashboards made with tools like Tableau, 
Power BI, and Google Data Studio. 

❖ These dashboards can offer up-to-the-minute information about COVID-19 instances 
and trends, empowering decision-makers to move quickly based on the most recent 
data. Additionally, patterns and anomalies in the data that may not be immediately 
obvious can be found with the aid of data visualization. For instance, visualization may 
show a spike in cases among a certain age group or demography, or a disproportionate 
number of cases in a given area. Public health officials may be able to more effectively 
focus their efforts and resources with the use of this information.

❖ Tableau is an effective application for data visualization that enables users to build 
interactive dashboards, charts, and graphs as well as study data in an intuitive and visual 
manner. Tableau was used in your project to analyse and visualize COVID-19 data, 
spot trends, anomalies, and outliers, as well as share important insights with 
stakeholders. To use Tableau for COVID-19 data visualization, you likely started by 
importing the data into the tool. Then, you may have created a dashboard that displays 
relevant metrics, such as total COVID-19 cases, deaths, and hospitalizations over time. 
You may have also created maps showing the geographic distribution of COVID-19 
cases and trends, or visualizations that show the impact of the pandemic on different 
demographics. 

❖ With Tableau's drag-and-drop interface, you can quickly create graphs and charts, and 
its robust analytics capabilities let you carry out advanced data analysis tasks like 
finding trends and outliers. You might have used Tableau to undertake statistical 
analysis to find relationships between various variables or to develop computations and 
filters that emphasize particular data points. 

❖ In addition to COVID-19 data visualization, Tableau is used in a broad variety of other 
fields and roles. It can be used to make dashboards that monitor customer behaviour, 
financial data, or corporate performance. It can also be used in medical settings to track 
patient outcomes or in scientific research to illustrate the findings of experiments.

❖ Tableau is an all-around effective and flexible application that can be used to view and 
analyse data in a variety of scenarios. It is a preferred option for data professionals and 
decision-makers in a variety of industries due to its simplicity of use, interactive 
features, and potent analytics.

❖ In conclusion, data visualization is a great technique for conveying complicated data in 
an understandable and efficient manner. In many different sectors and industries, its 
utilization is crucial for collecting knowledge and for arriving at well-informed 
conclusions.

DATA CLEANING:

❖ For the Hypothesis-1, we have used Date, Recip_State & Series_Complete_Yes
columns from one dataset (COVID-19 Vaccinations in the United States,County) in a 
tab named “vaccine” and state, covid_hospital_admissions_per_100k, date_updated 
column in a tab called “hospital” from the another dataset(United States COVID-19 
Community Levels by County). 
In the “hospital” tab one extra column “region” has been added to identify the regions 
of each state on which we are trying to analyze the data for the hypothesis and making 
the visualization. We have cleaned the dataset for each required column used in analysis 
and visualization by keeping the data that are insightful & value-added and have 
complete information.

❖ For the Hypothesis-2, we have used two datasets and they are United States COVID19 Community Levels by County and US States - Ranked by Population 2023. Both 
the datasets are cleaned using Excel and we extracted the needed columns from both 
the datasets for our visualization. The columns used from the dataset United States 
COVID-19 Community Levels by County and US States are State, 
covid_hospital_admissions_per_100k, covid_cases_per_100k, Date Updated. The 
columns used from the dataset US States - Ranked by Population 2023 are state, 
population 2022, area.

❖ For the Hypothesis-3, From the data set, we have used two columns, 
covid_cases_per_100k and covid_hospital_admissions_per_100k. 
From the initial data, we had more than 200K rows. But for our hypothesis, we only 
needed the data of the counties that are present in Texas. 
So first we filtered out the counties in Texas and then searched for any null values that 
might be in the data. Once the data cleaning has been done, the data was then imported 
into Tableau and used to prove our hypothesis.

❖ For the Hypothesis 4, we utilized various columns from multiple datasets. For instance, 
we used the UNVACCINATED_DEATHS, VACCINATED_DEATHS, and DATE 
columns to investigate the correlation between vaccination and COVID-19 death cases. 
Additionally, we extracted important data columns from several datasets and merged 
them into a single datasheet for better visualization. This included the 2022 Total 
Population and 2022 Total Population by Sex columns from the Census Bureau 
California Quick Facts dataset, combined with the Cumulative Fully Vaccinated 
column from the COVID-19 Vaccines Administered by Demographics dataset.

❖ For the Hypothesis 5, We used the Date, Recip_State, and Series_Complete_Yes 
columns from one dataset (COVID-19 Vaccinations in the United States, County) in a 
tab titled "vaccine" and the State, covid_hospital_admissions_per_100k, and 
date_updated columns from another dataset (United States COVID-19 Community 
Levels by County) in a tab titled "hospital". To identify the regions of each state on 
which we are attempting to analyze the data for the hypothesis and create the 
visualization, a new column labeled "region" has been added to the "hospital" tab. By 
maintaining the data that are insightful & value-added and have complete information, 
we have cleansed the dataset for each necessary column utilized in analysis and 
visualization.

❖ For the Hypothesis 6, below are the data cleaning steps for each required column:
date as of: The date when the data was last updated or collected.

Data cleaning: The column was likely left unchanged after cleaning since it provides 
important information about when the data was last updated.

Age group: The age group being analyzed in the data (e.g., 0-17, 18-29, 30-39, etc.).

Data cleaning: This column likely required cleaning to ensure that age groups were 
consistent across the dataset and there were no missing or invalid values.

covid 19 deaths: The number of deaths due to COVID-19 during the time period being 
analyzed.

Data cleaning: This column likely required cleaning to ensure that the data was accurate, 
consistent, and free of any missing or invalid values.

Pneumonia incidence: The number of cases of pneumonia during the time period being 
analyzed.

Data cleaning: This column likely required cleaning to ensure that the data was accurate, 
consistent, and free of any missing or invalid values.

Pneumonia and covid 19 deaths: The number of deaths due to pneumonia and COVID19 during the time period being analyzed.

Data cleaning: This column likely required cleaning to ensure that the data was accurate, 
consistent, and free of any missing or invalid values.

state: The state or territory for which the data is being reported.

Data cleaning: This column likely required cleaning to ensure that state names were 
consistent across the dataset and there were no missing or invalid values.

INSIGHTS & FINDINGS:

Hypothesis 1: 

Whether the Hospital admission rate in the Northern region of the USA is 3% 
less than in the Southern region of the USA because 11% more vaccination per 100k has been 
administered in the Northern region of the USA in the year of 2022.

![alt text](https://github.com/Lohya/Data-Visualization-Project/blob/main/Hypothesis%201%20Image.png)

Insights:

1. We have made two sets of regions from north states and south states of USA, to 
make a comparison between the data values of two regions. In the visualization, 
the north region is blue color and the south region states are orange color (1st plot).

2. The Hospital Admission rate ratio of the North & South Region of USA states in 
the year 2022. The north region in the USA holding 48.626 %, and the south region 
states holding 51.374%. The difference is approximately 3%, which aligns with the 
data in the 1st part of the hypothesis. (In the 2nd picture, north region is in the blue 
color, south region states in the orange color)

3. We tried to analyze the Vaccination trend in the north and the south region in the 
year 2022. The graph showed us the rise & fall of the vaccination counts in each 
region. Though we got a similar type of graph for vaccination for both regions, if 
we check the value from the y-axis, it's not exactly the same. While doing the detail 
analysis of the vaccination data month wise, we saw there is a visible huge fall from 
May to July for both regions and then a slight rise and fall till December. From here, 
we can conclude that from May to July 2022 duration a huge number of the 
17
population stopped taking vaccines in both regions. From the Data set, we got the 
calculation that approximately 11% more vaccination per 100k has been 
administered in the Northern region of the USA. So, our hypothesis is proved right. 
(3rd picture from the left in the presentation)

4. Next, we tried to analyze the Hospital admission rate movement for the north & 
south region in the year 2022. We could find the difference in hospitalization rates 
between each region and each month and how the hospitalization rate changes 
month wise. If we compare the previous graph with this one, we would see the 
correlation between vaccination & hospital admission rate. For the North region, in 
the month of May to July, the vaccination fell drastically, and hospital admission 
rates increased noticeably. After the month of August, the hospital admission fell 
as there was a stable count of vaccination received by the people. From the 3rd 
graph, After the month of November, the vaccine count started going down 
gradually, and we can see the hospital admission rate also started going up, so there 
is clearly an inverse correlation between the vaccination and the hospital admission 
rate, as we already found Northern region is having 3% less hospitalization rate & 
11% more vaccination rate which proves our hypothesis as correct. (4th 
graph/picture in the visualization)

Findings:

1. The findings revealed a reduction in both the severity and the duration of long covid 
symptoms in people who were vaccinated.

2. Vaccination markedly reduced adverse outcomes, with non-ICU hospitalizations, 
ICU hospitalizations, and deaths decreased.

3. Since vaccinated patients admitted in the ICU are much more likely to survive than 
their unvaccinated counterparts (4), the vaccinated patient is likely to be prioritized 
over the unvaccinated.

4. those who received the vaccine were at an 80% lower risk of developing disease 
than the group who received the placebo. This is calculated by comparing the 
number of cases of disease in the vaccinated group versus the placebo group.

5. People who have received booster doses have an even lower risk of hospitalization 
or death than people with similar risk factors who have only received a primary 
series of vaccine or people who are not vaccinated

6. It was found that the new cases per million and new deaths per million increased as 
the rate of people fully vaccinated per hundred increased.

7. COVID booster actually prevented hospitalization and measures are: 1 period, but 
a third and fourth dose provided additional protection to eligible adults, the Centers 
for Disease Control and Prevention reported Friday. Based on data from 10 states, 
two doses were 61% effective against hospitalization during the BA. 1 period and 
24% effective during the BA.

8. Once fully vaccinated, participants' risk of infection was reduced by 91%. After 
partial vaccination, participants' risk of infection was reduced by 81%.

Hypothesis-2:

In the state of Virginia, the covid cases are 80.8% more and the hospital 
admission rate is 78.8% more than in the state of Washington even when they have a similar 
population because the population density of Washington is 60.9% less than that of Virginia 
in the year 2022.

![alt text](https://github.com/Lohya/Data-Visualization-Project/blob/main/Hypothesis%202%20Image.png)

Insights:

1. In sheet 1 we can see where the states of Washington and Virginia are located, 
we can see that they are located on the opposite coasts.

2.The area of the state of Virginia is lesser compared to the state of Washington.

3. In sheet 3 we have taken the number of cases for both the states for every month 
in 2022 from February to December and the cases in the state of Virginia are 
consistently more than in the state of Washington.

4.In the sheet 4, we took the covid hospital admission per 100k in the year 2022 
and even in this state of Virginia has shown more hospital admissions than the state 
of Washington.

5. The size of the character used in the visualization is directly proportional to the 
population of the state.

Findings:

1.From the dashboard of our visualization, we can conclude that the area for the 
state of Virginia is 68.2% less than the area of the state of Washington.

2. The population of both the states is similar as the size of the character used in 
the visualization is same.

3. Both Covid Cases and Covid Hospital Admissions are higher in the state of 
Virginia every month considered than the state of Washington even with similar 
population because of the proximity of the people in Virginia is more and proximity 
of the people is less when compared to Virginia in the state of Washington as the 
population density of Washington is 60.9% less than that of state of Virginia.

Hypothesis-3: 

In the state of Texas, the hospital admission rate of Colorado county is 37% 
higher than Angelina County, because of 71% higher covid cases in Colorado county.

![alt text](https://github.com/Lohya/Data-Visualization-Project/blob/main/Hypothesis%203%20Image.png)

Insights:

1. According to the hypothesis, there may be a significant correlation between Colorado 
County's hospital admission rate and the number of COVID patients there.
 
2. According to the theory, there are more COVID cases in Colorado County because of 
the higher hospital admission rate.

3. If the hunch is correct, it would mean that Colorado County's healthcare system is 
dealing with a greater need for hospitalization because of COVID-19 cases, resulting 
in a higher hospital admission rate as compared to Angelina County.

4. Different population demographics, variances in the accessibility of healthcare services, 
or variations in the adherence to public health recommendations could all be 
contributing factors.

5. To confirm or disprove the theory, more investigation would be required, including 
looking at information on healthcare resources, demography, and COVID-19 
transmission rates in both counties.

6. The association between COVID cases and hospital admission rates should also take 
into account any potential confounding factors that may affect the relationship, such as 
variations in the prevalence of other health problems or variations in hospitalization 
policy between the two counties.

Findings:

1. It implies that there is a significant relationship between Colorado County's hospital 
admission rate and the number of COVID patients there.

2. As more COVID cases would result in a higher demand for hospitalization, the 71% 
increase in COVID cases in Colorado County as compared to Angelina County may be 
a significant contributor to the county's higher hospital admission rate.

3. It's crucial to remember that correlation does not inevitably imply causation.
 
4. Different healthcare access, demography, or healthcare regulations might be affecting 
Colorado County's hospital admission rate in addition to these other variables.

5. Additional investigation would be required to verify the results of this hypothesis and 
to find any additional potential causes for the disparity in hospital admission rates 
between the two counties.

6. In order to do this, it may be necessary to examine data on healthcare resources, 
demographic traits, and COVID-19 transmission rates as well as any confounding 
variables.

Hypothesis 4: 

In California for the year 2022, COVID-19 deaths among males are 17.06% 
higher than among females. This can be attributed to the fact that the female group has a higher 
vaccination rate than the male group.

![alt text](https://github.com/Lohya/Data-Visualization-Project/blob/main/Hypothesis%204%20Image.png)

Insights：

1. The vaccination shows a significant impact on reducing COVID-19 deaths. A stacked 
bar chart illustrates that the highest number of death cases occurred in the first quarter 
of the year, from January to March. In 2022, the number of unvaccinated death cases 
in California was 14,140,000, while the number of vaccinated death cases was 
3,050,000. This represents a staggering 78.43% higher in unvaccinated death cases 
compared to vaccinated death cases. It’s obvious that the majority of COVID-19 deaths 
in California are attributed to unvaccinated cases. These findings highlight the 
significant impact of vaccination in reducing COVID-19 deaths, particularly in the state 
of California.

2. COVID-19 shows a gender bias, with a higher number of male deaths compared to 
females in California for most months in 2022. When looking at the COVID-19 
deaths situation in California in more detail over time, a discrete line chart shows over 
the course of 12 months, male COVID-19 deaths were consistently higher than female 
deaths. In 2022, the COVID-19 mortality rates in California were higher among males 
than females, with 48.53% (or 6,322,370 deaths) of total COVID-19 deaths occurring 
among males and 41.47% (or 4,478,974 deaths) occurring among females, resulting in 
a 17.06% higher death rate among males than females. It is important to note that the 
gender ratio in California, as per the U.S. Census Bureau's data for 2022, is 0.99, 
indicating that the population is evenly distributed between males and females. This 
suggests that the 17.06% disparity in COVID-19 deaths between males and females is 
not due to a difference in population distribution.

3. In California in 2022, females had a higher COVID-19 vaccination rate compared to 
males. The Gannet graph generated from the cumulative vaccinated data clearly shows 
that in 2022 in California, females consistently had a higher vaccination rate than males. 
As of December, the female group had an approximately 75% vaccination rate, while 
the male group had a 70% vaccination rate, resulting in a 5% higher vaccination rate 
among females. These findings provide further evidence that vaccination rates are a 
significant factor in explaining the difference in COVID-19 deaths between males and 
females.

Findings:

❖ Based on the data presented, it appears that there is a significant difference in COVID19 death cases between males and females in California in 2022, with males 
experiencing a 17.06% higher death rate than females. Our analysis suggests that 
differences in vaccination rates may play a significant role in explaining this difference, 
with females consistently having a higher vaccination rate than males throughout the 
year. However, it is important to note that this difference in mortality rates may also be 
influenced by various other factors such as differences in immune response, lifestyle 
factors, and underlying health conditions. Therefore, further analysis is necessary to 
fully understand the underlying causes of the observed mortality rate differences. 
Nonetheless, increasing vaccination rates among males could be a key strategy in 
reducing COVID-19 deaths in California.

Hypothesis 5: 

COVID-19 pandemic has significantly impacted the US labor force because 
employment decreased by 3.2 percentage from January 2020 to August 2021.

![alt text](https://github.com/Lohya/Data-Visualization-Project/blob/main/Hypothesis%205%20Image.png)

Insights:
 
1. The US labor force has been significantly impacted by the COVID-19 pandemic. The 
US unemployment rate, according to the Bureau of Labor Statistics, rose abruptly from 
3.5% in February 2020 to 14.8% in April 2020 before progressively falling to 5.2% in 
August 2021

2. The 3.2 percentage point decline in employment that you mentioned is a sizable decline. 
It suggests that the epidemic has caused millions of employees to lose their employment 
or be required to work fewer hours.

3. It's crucial to remember that the work force has been progressively recovering since the 
pandemic's peak. Even though the employment rate has been rising over the past year, 
it is still lower than it was before the pandemic.

4. Low-wage employees, women, and people of color are just a few of the groups in the 
workforce who have been disproportionately impacted by the pandemic. These groups 
have seen higher rates of job loss and fewer hours worked, which has increased labor 
market inequality already present.

5. The pandemic's effects on the labor force have not been the same in all economic sectors. 
While other sectors, like healthcare and professional services, have fared relatively well, 
others, like leisure and hospitality, retail, and transportation, have been hit particularly 
hard.

Findings:

1. According to the Bureau of Labor Statistics (BLS), the US experienced a sharp increase 
in unemployment rates following the onset of the COVID-19 pandemic. In February 
2020, the unemployment rate was at a low 3.5%, but by April 2020, it had skyrocketed 
to 14.8%. Although it has since declined, the unemployment rate remained high 
throughout 2020 and 2021, reaching a peak of 6.3% in January 2021.

2. In addition to the high unemployment rates, there was a significant decrease in 
employment across various industries. The BLS reports that the pandemic has caused 
job losses across many sectors, with the largest declines in leisure and hospitality, 
followed by education and healthcare.

3. Further, the pandemic has disproportionately affected specific groups within the labor 
force, such as women, minorities, and low-wage workers. Women have been more 
likely to lose their jobs due to pandemic-related closures and caregiving responsibilities, 
while people of color have experienced higher rates of job loss than their white 
counterparts.

Hypothesis 6: 

Whether the Pneumonia and Covid-19 deaths are 71% higher in the age group 
65-74 compared to the age group 40-49 due to 74% higher incidence of pneumonia in the age 
group 65-74 in the year 2022.

![alt text](https://github.com/Lohya/Data-Visualization-Project/blob/main/Hypothesis%206%20Image.png)

Insights:

1. The hypothesis suggests that there may be a correlation between higher incidence of 
pneumonia and COVID-19 and higher mortality rates in the age group 65-74 compared 
to the age group 40-49 in the United States.

2. The hypothesis proposes that the 74% higher incidence of pneumonia in the age group 
65-74 is responsible for the 71% higher mortality rates due to pneumonia and COVID19 in that age group compared to the age group 40-49.

3.The hypothesis suggests that there is a significant age-based discrepancy in the 
mortality rates due to pneumonia and COVID-19 in the United States. Specifically, the 
age group 65-74 appears to be at a higher risk for mortality compared to the age group 
40-49.

4. The hypothesis proposes that the higher incidence of pneumonia in the age group 65-
74 is responsible for the higher mortality rates in that group. This indicates that 
pneumonia may be a significant contributor to the overall mortality rates due to 
COVID-19, as COVID-19 can cause pneumonia in some cases

5. It is important to note that the hypothesis is focused on the year 2022, which assumes 
that the incidence rates of pneumonia and COVID-19 will remain constant in that year. 
However, the actual incidence rates of these diseases can be influenced by various 
factors such as vaccination rates, changes in public health policies, and new strains of 
the virus.

6. Further analysis is needed to determine if the higher mortality rates due to pneumonia
and COVID-19 in the age group 65-74 are a result of delayed or inadequate treatment, 
comorbidities, or other factors that may be associated with aging. This information can 
help to develop targeted interventions that improve health outcomes for this age group.
8. The hypothesis highlights the importance of monitoring and reporting mortality rates 
due to pneumonia and COVID-19 in different age groups. This can help to identify and 
address disparities in health outcomes and guide public health policies and 
interventions.

7. The hypothesis highlights the potential impact of social determinants of health on 
mortality rates due to pneumonia and COVID-19. For example, factors like poverty, 
limited access to healthcare, and inadequate housing can increase the risk of respiratory 
infections and contribute to poorer health outcomes. Addressing social determinants of 
health may be an important strategy for reducing mortality rates due to pneumonia and 
COVID-19 in different age groups.

Findings:

1. Further analysis is needed to establish a causal relationship between the incidence of 
pneumonia and COVID-19 and the mortality rates in different age groups. Other factors 
such as pre-existing medical conditions, access to healthcare, and socio-economic 
status may also contribute to the higher mortality rates in the age group 65-74.

2. Continuous monitoring and analysis of the data is important to identify trends, patterns, 
and potential risk factors that may contribute to higher mortality rates in different age 
groups and populations.

3. In order to reduce mortality rates due to pneumonia and COVID-19, preventative 
measures such as vaccination and early diagnosis and treatment of these diseases may 
be beneficial, particularly for individuals in the age group 65-74 who are at higher risk.

4. The hypothesis suggests that there may be a significant burden on healthcare systems 
and caregivers due to the higher mortality rates in the age group 65-74. This highlights 
the importance of adequate healthcare resources and support for this age group.

5. The hypothesis raises the question of whether vaccination rates and access to healthcare 
services may contribute to the higher incidence rates of pneumonia in the age group 65-
74. This indicates that preventative measures such as vaccination and improved access 
to healthcare may be important strategies for reducing the incidence and mortality rates 
of pneumonia and COVID-19 in this age group.

6.The hypothesis highlights the potential impact of comorbidities on mortality rates due 
to pneumonia and COVID-19 in different age groups. This suggests that targeted 
interventions to manage and prevent comorbidities may be important for improving 
health outcomes in older adults.

7. The hypothesis emphasizes the importance of accurate and timely data collection and 
analysis for understanding the epidemiology of pneumonia and COVID-19. This can 
inform public health policies and interventions that aim to reduce the incidence and 
mortality rates of these diseases.

8. The hypothesis underscores the need for further research to better understand the 
mechanisms underlying the relationship between pneumonia and COVID-19, and how 
this relationship contributes to mortality rates in different age groups. This can inform 
the development of effective treatments and interventions for these diseases.

Conclusion:

❖ Coronavirus disease (COVID-19) is an infectious disease caused by the SARS-CoV-2 
virus. Most people infected with the virus will experience mild to moderate respiratory 
illness and recover without requiring special treatment. The crisis had a dramatic impact 
on global poverty and inequality. Global poverty increased for the first time in a 
generation, and disproportionate income losses among disadvantaged populations 
dramatically increased inequality within and across countries. We should follow a few 
rulesets such as: avoid close contact with people who are sick, avoid touching your eyes, 
nose, and mouth with unwashed hands. Clean and disinfect frequently touched objects 
and surfaces. Use an alcohol-based hand sanitizer with at least 70% alcohol if you have 
symptoms of acute respiratory illness. In those situations, use as many prevention 
strategies as you can, such as practicing hand hygiene, consistently and correctly 
wearing a high-quality mask, improving ventilation, and keeping your distance, when 
possible, from the person who is sick or who tested positive.

❖ While researching the data, we have come to a few conclusions. Those are as below:
From the data, we calculate that the hospitalization rate for the vaccinated population 
is 0.01% (or 1 in 10,914). The rate for unvaccinated adults is 0.89% (or 1 case in 112 
people). Vaccination remains the safest strategy for avoiding hospitalizations, longterm health outcomes, and death. Protection against getting infected does appear to 
wane over time. Protection against death and severe disease also drops over time, but 
more slowly. You can increase your protection by getting a booster from 6 months after 
your primary course.

❖ The global effects of the pandemic are profound: The COVID-19 pandemic has clearly 
had a significant influence on people's lives and health all around the world when the 
number of cases, fatalities, and hospitalizations are visualized. The pandemic has had 
varying effects on different geographical areas: Significant variations in the prevalence 
and effects of COVID-19 can be seen when the data is shown by nation or region. For 
instance, certain nations were affected more severely than others, and some areas saw 
more severe epidemics than others














