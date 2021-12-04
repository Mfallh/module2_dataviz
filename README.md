# Module 2 Project: Data Visualization : Impact of COVID on Happiness 

## Overview

The objective of our project was to source and interpret real world data and to practice creating and interpreting different types of visualizations using real world data.

We decided to focus on measuring the impact of COVID on happiness via the data found in the [World Happiness Report](https://worldhappiness.report/ed/2021/) 

---

## Deliverables 

- **Jupyter notebook** Import of data set, harmonization/cleaning of data, visualization of data 
- **data folder** containing your data set
- **PPT presentation** presentation in French to satisfy the storytelling requirement with accompagning visualizations 
- **Trello** Our planning tool:[Trello](https://trello.com/b/s6krGprT/project-module-2-data-viz-taler-marius)


## Sources: 

* **World Happiness Report** - Yearly report that documents how happiness of participating countries' citizens with 6 factors [World Happiness Report](https://happiness-report.s3.amazonaws.com/2021/WHR+21.pdf), and accompagning dataset used : [World Happiness Report Data Panel](https://happiness-report.s3.amazonaws.com/2021/DataPanelWHR2021C2.xls)
* **ISO-3166 Country and Dependent Territories Lists with UN Regional Codes from users Lukes, jlewis91,michalskop,NickDickinsonWilde via Github** - Merged lists ISO 3166-1 country classication and  UN Geoscheme regional codes in ready-to-use JSON, XML, CSV data sets  or the [ISO-3166 Country and Dependent Territories Lists with UN Regional Codes](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/6b31edc760abcceb7aa1ae4f15e6e4496bce97f1/all/all.csv)

## 6 factors of Happiness According to the World Happiness Report 

All scores are based on its relation to an imaginary control country, 'Dystopia' that has the least happiest population by all criteres measured by this report. Dystopia's score should match up with the lowest averages scores found from actual countries data and therefore work as an benchmark. 

The total score features a Cantril Ladder model from 0-10, the higher the score on the ladder, the happier a country's population. This result comes from an annual Gallup poll  The remaining 6 factors - levels of GDP, life expectancy, generosity, social support, freedom, and corruption - are  averaged calculations from 2018-2020 that show what share of these factors determine why why one's country total score is higher than another[(see World Happiness Report FAQ for more info)](https://worldhappiness.report/faq/#where-do-the-subbars-come-from-for-each-of-the-six-explanatory-factors).

## Final Data Set 

Our final dataset has the following columns:

| **Factors**|**Score and Description**|
|-----|-----|
| Life Ladder|Cantril Ladder results from annual Gallup Poll, 0-10 |
| GDP Per Capita|Calculation of strength of GDP in relation to Dystopia, 0-10 |
| Social support | Calculation of feeling of community among other population members, 0-1 |
| Life Expectancy|Calculation of Life Expectancy vs Coefficient of Average Coefficient |
| Freedom to make life choices| Calculation of relative social freedom, 0-1 |
| Perception of corruption| Calculation of perception of corrpution, 0-1 |
| Positive Affect| Positive affect is defined as the average of three positive affect measures set by GWP: happiness, laugh and enjoyment,measured from 0-1 |
| Negative Affect| Negative affect is defined as the average of three negative affect measures set by GWP: They are worry, sadness and anger,measured from 0 -1 |
| Region|Location of countries by continent |
| Sub-region| classification of countries by the regions they are found in their respective continents |
