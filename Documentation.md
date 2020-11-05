The brief: the world happiness report is an annual document that looks surveys participants from countries across the globe to identify A) what countries are the happiest and B) what factors contribute the most to a country's happiness.
In their analysis they generate ratings for the economy, health, family, freedom and trust (in government) to help complile and overall happiness score.
For our project we're looking to use the data from this report along with other attributes to create a machine learning model that can predict the happiness of a country/region based on the values of these inputs

Identifying key characteristics
To start with we'll look to try and identify factors that are highly correlated with the happiness result. To do this we'll collect datasets and do tests to determine how highly that data is correlated with the happiness score (through linear regression)
Use random tree to help analyse the breakdown of factors


Cleaning Data
Clean up data by removing n/a values, identifying gaps in data, not all datasets will have entries for all countries and identify outliers. Breakdown how non continuous variable will be categorised.
Part of this process will include how the countries are categorised e.g developed/developing, urban/rural, poverty rates etc, geography


Standardising Data
Important to ensure all data is uniform and standardised e.g same $ value, per capita etc. May need to standardise data in case where there's a large range of values.

Train Model
At the stage we'll train the model with the data. We may train several models to take into account the different backgrounds/circumstances of the country so that it can have a more accurate output. 

Visualise Results
Once we have the output from the model the various results will be visualised through Tableau Public. May create website interface to interact with machine learning model if appropriate

List of potential factors to look at:
- suicide rate
- religion 
- gender
- renewables
- literacy
- gay marriage
- internet
- energy access
- infrastructure
- sport
- debt
- family size
- weather/sunlight
- education (ignorance is bliss)
- alcohol
- population density
- dwelling type
- size of community
- contraceptives
- universal healthcare
- coastline
- longitude/latitude
- diabetes rates
- patriotism 
- cultural diversity
- Olympics?
- diet
- national parks, world heritage listed sites
- air pollution
- hours worked per week
- charity
- tourism
- proximity to other countries
- number of holidays 
- disease
- divorce rates
