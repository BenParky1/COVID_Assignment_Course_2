# COVID_Assignment_Course_2

Week 2 Observations
The data in the gibraltar dataframe doesn't look correct. There are more hospitalisations than cases from 2020-03-27. The data in the deaths, cases and recovered columns look cumulative whilst the hospitalised values are not. It is assumed that this is the data for that specific date. this is also the case for the full cov dataframe

There are default indexes on both the vac and cov dataframes, the data in both looks like it is recorded in the same order (ie index 0 of the cov dataframe corresponds to index 0 of the vac dataframe). This could be useful if possible to merge the dataframes together. There are columns which are unnecessary for this analysis such as Lat, Long and Sub-region name. I am going to use the Province/State to compare different areas.

Are there any visualisations that could be added here to make it easier?
Line charts of changing variables over time would be useful as this would make it easier to see how this data is behaving.

What would I like to explore further?
I would like to be able to merge the cov and vac dataframes to allow me to analyse the impact vaccinations has on deaths, cases and hospitalisations. I would also like to analyse the speed of the vaccine roll out in different states by viewing the data in a line graph over time.

Week 3 Notes

Gibraltar has administered the most vaccinations in total, but also has the highest number of people who have only had one dose. It is worth noting at this point that the summed values seem very high (5.8 million 1st doses administered in Gibraltar).

The data for province/state "Others" doesnt seem correct as the ratio of deaths to recovered is not consistent with other provinces. This data has been dropped from the analysis as I feel I cannot trust it.

The merged dataframe contains cumulative data for some columns and non-cumulative data for other columns.

The percentage of people who after the first dose went on to have the second dose is consistent accross all provinces at around 95%. I am unable to determine what percentage of the population has been vaccinated as I do not have the population data for each province.

A column for deaths per number of cases has been created to compare different Provinces as deaths data alone cannot be used as it is unknown what percentage of the Province population this is.

The dataframes now seem in a state that will allow the data to be plotted on visualisations that can be analysed easier. This will allow the business questions to be answered.
