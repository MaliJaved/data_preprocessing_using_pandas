# World Happiness Report Dataset
### Overview

🌐 Greetings GitHub community! I am pleased to share my project on the World Happiness Datasets using Python.

The project encompassed the consolidation of data from the years 2016, 2017, and 2018, with a focus on employing pandas for effective data handling. Emphasis was placed on data cleanliness through the removal of duplicates and the systematic addressing of missing values, resulting in the creation of a refined dataset conducive to analysis.

### Libraries Used
- Pandas
- Matplotlib
- Seaborn

### About Dataset

**Context:**
The World Happiness Report is a global survey of happiness levels, with reports published annually. It's used by governments and organizations to inform policy decisions and assess well-being. The report ranks countries based on their happiness scores.

**Content:**
- The dataset includes happiness scores and rankings derived from the Gallup World Poll.
- Respondents rate their own lives on a scale from 0 (worst) to 10 (best).
- It covers data from 2013-2016 and uses Gallup weights for representativeness.
- Six factors contributing to happiness are included: economic production, social support, life expectancy, freedom, absence of corruption, and generosity.

**Inspiration:**
- Researchers can explore which countries are the happiest.
- Changes in country ranks or scores between reports can be analyzed.
- Significant increases or decreases in happiness can be identified.

### What is Dystopia Residual?

The "Dystopian Residual" column in the dataset is like a measure of how far away a country's happiness is from the worst possible situation, which is called "Dystopia." 

Imagine if there was a place in the world where people were the most unhappy, where everything is really bad – the lowest income, the shortest life expectancy, the least freedom, the least support from others, the least generosity, and the most corruption. That place would be the Dystopia.

Now, the "Dystopian Residual" for each country in the dataset tells us how much better or worse that country is compared to the Dystopia. If a country has a positive Dystopian Residual, it means that it's happier than the Dystopia, and if it has a negative Dystopian Residual, it means it's less happy than the Dystopia.

So, in simple terms, the Dystopian Residual shows how a country's happiness compares to the absolute worst conditions in the world. Positive values mean the country is happier than the worst, and negative values mean it's less happy than the worst.

### Columns Description

The "World_Happiness_2015.csv" dataset appears to contain information related to the World Happiness Report for the year 2015. Let's break down the columns in simple words:

1. **Country**: This column contains the names of different countries around the world. Each row corresponds to a specific country.

2. **Region**: This column categorizes the countries into different geographical regions or areas, such as "Western Europe," "North America," etc. It helps organize the data by location.

3. **Happiness Rank**: This column ranks the countries based on their levels of happiness, with 1 being the happiest. It shows which countries are the happiest and which are less happy.

4. **Happiness Score**: The happiness score is a numerical value that represents how happy a country's population is. It's a measure of overall happiness, with higher scores indicating higher happiness levels.

5. **Standard Error**: This column provides a measure of the statistical error in the happiness score. It tells us how certain or uncertain the happiness score is for each country.

6. **Economy (GDP per Capita)**: This column measures the economic well-being of a country by looking at its Gross Domestic Product (GDP) per capita. It reflects the average income of the citizens.

7. **Family**: This column assesses the strength of social support or family relationships within a country. It reflects how connected and supportive people are within their families.

8. **Health (Life Expectancy)**: It indicates the average life expectancy in a country. This measures the health and well-being of the population, as longer life expectancies are generally considered positive.

9. **Freedom**: This column represents the level of personal freedom and choices available to the citizens of a country. It measures the extent to which people can make decisions about their lives.

10. **Trust (Government Corruption)**: This column measures the perception of trust in a country's government and institutions. It reflects the level of corruption or honesty within the government.

11. **Generosity**: This column gauges the generosity of the population, such as charitable donations and helping others. It assesses the willingness of people to share and help those in need.

12. **Dystopia Residual**: This is a hypothetical reference point used in the calculation. It represents the lowest possible happiness score a country could have, based on the lowest values for the other factors.

---
