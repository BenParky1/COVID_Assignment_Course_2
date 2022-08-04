# COVID_Assignment_Course_2
Week 2 Observations
The data in the gibraltar dataframe doesn't look correct. There are more hospitalisations than cases from 2020-03-27. The data in the deaths, cases and recovered columns look cumulative whilst the hospitalised values are not. It is assumed that this is the data for that specific date. this is also the case for the full cov dataframe

There are default indexes on both the vac and cov dataframes, the data in both looks like it is recorded in the same order (ie index 0 of the cov dataframe corresponds to index 0 of the vac dataframe). This could be useful if possible to merge the dataframes together. There are columns which are unnecessary for this analysis such as Lat, Long and Sub-region name. I am going to use the Province/State to compare different areas.

Are there any visualisations that could be added here to make it easier?
Line charts of changing variables over time would be useful as this would make it easier to see how this data is behaving.

What would I like to explore further?
I would like to be able to merge the cov and vac dataframes to allow me to analyse the impact vaccinations has on deaths, cases and hospitalisations. I would also like to analyse the speed of the vaccine roll out in different states by viewing the data in a line graph over time.
