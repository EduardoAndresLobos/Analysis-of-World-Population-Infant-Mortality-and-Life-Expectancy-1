# Analysis of World Population,Infant Mortality and Life Expectancy

<h3>In the first World Population report, 3 .xlsx files are loaded </h3>

Population, contains a list of countries and number of habitants.
Countries, contains list of countries, country code and its respective continent.
all the data that is not going to be used is hidden, in this case the Countries table and the Country column of the Population table.

In the second Mortality and Life Expectancy, 2 additional .xlsx files are uploaded

Infant+death+rate, contains a list of countries and the average number of infant deaths per 1,000 deaths.
Life+expectancy, contains a list of countries and the average life expectancy.


<h3>The following relationships are generated in the data model: </h3>

![image](https://user-images.githubusercontent.com/112581327/187766219-a8782e64-82ce-43d9-84f2-cd42395fe383.png)



<h3>World Population Report </h3>

A Treemap with the number of habitants per country
A Matrix where we can see the detail of habitants by continent and country
A Map where you can see the distribution of countries by continent, the bubbles are conditioned to the size of the population of each country
In addition to the segmented filter, the number of habitants was added one per continent

![image](https://user-images.githubusercontent.com/112581327/187766579-c1fe018c-31ab-48b7-9be4-a598424e285f.png)

<h3>In Power Query a conditional column is generated to segment countries into 4 categories: </h3>

0 - 1M
1M - 10M
10M - 100M
100M >
With this segmentation a filter is added

![image](https://user-images.githubusercontent.com/112581327/187766973-f81a4644-b689-4e06-a891-a303626b1b13.png)


<h3>Infant Mortality and Life Expectancy Report </h3>

A Matrix where we can see the detail of inhabitants by continent and country, average Life Expectancy and average Infant Mortality
Scatter plot, studying the relationship between life expectancy and infant mortality
A Map where you can see the distribution of countries by continent, the bubbles are conditioned to the size of Infant Mortality


![image](https://user-images.githubusercontent.com/112581327/187767180-3bac8288-cea4-46bd-9274-06fa8e6260ba.png)

<h3>In Power Query a conditional column is generated in each table to slice: </h3>

Child mortality
0 to 10
10 to 25
25 0 50
50 >

![image](https://user-images.githubusercontent.com/112581327/187767326-fe2cf6c6-302d-48b1-a566-caf16c7f70df.png)


<h3>Some conclusions that can be drawn from this report </h3>
The lower life expectancy, the higher infant mortality, with the African continent being the most affected by this trend.
Angola represents the most affected country since its average life expectancy is 56 years and an infant mortality rate of 191 per 1,000 deaths.
The least affected country in Monaco belonging to the European continent with an average life expectancy of 89 years and an infant mortality of 5 per 1000 deaths
