# COVID-19 Data Analysis

The Covid-19 pandemic has brought about numerous short-term and long-term consequences for human health, society, the economy, and the environment. The outbreak of this pandemic in 2019 has resulted in significant ripple effects on the daily lives of individuals and the global economy.

Currently, the impact of Covid-19 on everyday life is extensive and has profound implications.

For this project, I conducted an analysis and exploration of Covid-19 data using SQL through Microsoft SQL Server Management Studio.

The Covid-19 data used for this analysis was obtained from Our World in Data, covering the period from January 1, 2020, to July 12, 2023.

***ABOUT THE DATABASE***

You can access the database tables for the starter project of the Our World in Data COVID-19 datasets by visiting the following URL: https://ourworldindata.org/covid-deaths. The tables can be found within the "database" folder.


CovidDeaths: 
contains columns such as 
isocode continent	location	date	population	total_cases	new_cases	new_cases_smoothed	total_deaths	new_deaths	new_deaths_smoothed	total_cases_per_million	new_cases_per_million	new_cases_smoothed_per_million	total_deaths_per_million	new_deaths_per_million	new_deaths_smoothed_per_million	reproduction_rate	icu_patients	icu_patients_per_million	hosp_patients	hosp_patients_per_million	weekly_icu_admissions	weekly_icu_admissions_per_million	weekly_hosp_admissions	weekly_hosp_admissions_per_million

CovidVaccinations: 
contains columns such as 
isocode continent	location	date	new_tests	total_tests	total_tests_per_thousand	new_tests_per_thousand	new_tests_smoothed	new_tests_smoothed_per_thousand	positive_rate	tests_per_case	tests_units	total_vaccinations	people_vaccinated	people_fully_vaccinated	total_boosters	new_vaccinations	new_vaccinations_smoothed	total_vaccinations_per_hundred	people_vaccinated_per_hundred	people_fully_vaccinated_per_hundred	total_boosters_per_hundred	new_vaccinations_smoothed_per_million	new_people_vaccinated_smoothed	new_people_vaccinated_smoothed_per_hundred	stringency_index	population_density	median_age	aged_65_older	aged_70_older	gdp_per_capita	extreme_poverty	cardiovasc_death_rate	diabetes_prevalence	female_smokers	male_smokers	handwashing_facilities	hospital_beds_per_thousand	life_expectancy	human_development_index	excess_mortality_cumulative_absolute	excess_mortality_cumulative	excess_mortality	excess_mortality_cumulative_per_million

In this project, various SQL techniques have been utilized to extract valuable information from the data. These techniques include joining tables, employing Common Table Expressions (CTEs), utilizing temporary tables, applying window functions, and utilizing aggregate functions. These methods enable us to gain insights and draw conclusions from the data. Additionally, as part of the project, we create views to store the outcomes of our analyses. These views serve as a foundation for further exploration, data visualization, and generating reports.

Through the analysis of COVID-19 data using SQL,  project's objective is to provide meaningful and valuable insights regarding the virus's impact on different regions. It also aims to evaluate the effectiveness of vaccination campaigns and comprehend the severity of the pandemic over time. The discoveries made in this project can aid in making well-informed decisions, allocating resources efficiently, and formulating effective public health strategies.




