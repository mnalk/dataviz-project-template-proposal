
# Data Visualization Project Name : Suicide prevention visualization project

## Data

The data I propose is to visualize for suicide prevention dataset that pulled from four other datasets linked by year and country, and was built to find signals correlated to increased suicide rates among different cohorts globally, across the socio-economic spectrum.

References United Nations Development Program. (2018). Human development index (HDI). Retrieved from [source](http://hdr.undp.org/en/indicators/137506)

World Bank. (2018). World development indicators: GDP (current US$) by country:1985 to 2016. Retrieved from [source](http://databank.worldbank.org/data/source/world-development-indicators#) [Szamil]. (2017). Suicide in the Twenty-First Century [dataset]. Retrieved from [source](https://www.kaggle.com/szamil/suicide-in-the-twenty-first-century/notebook)

World Health Organization. (2018). Suicide prevention. Retrieved from [source](http://www.who.int/mental_health/suicide-prevention/en/)

[Inspiration Suicide Prevention](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016?select=master.csv)

## Prototypes

First, I studied the suicide concept, and then I reviewed several sources to learn which attributes are more important than others.

Here are my attempts to understand the suicide consent :

1)[Data set : Number with depression by country in vizhub](https://vizhub.com/mnalk/fea0c634364d46ed8fd79d08eb72947c)
This data set help to understand how many people in each country have depression.

[Dataset description:](https://gist.github.com/mnalk/55e775e87b4232179fdd45a1db9ec129#file-readme-md)
[csv file:](https://gist.github.com/mnalk/55e775e87b4232179fdd45a1db9ec129#file-number-with-depression-by-country-csv)

Sketch for dataset(Number with depression by country)was a process to creat ideas below. The methodology used is [five design sheet](http://fds.design/)

[1)Sheet1 brain storm Ideas, Filter, Categorize, Combine/Refine, Question](https://drive.google.com/file/d/1NCOTkhhsna9SWYfg8CBFj2H690CpC4hv/view?usp=sharing)
[2)detailed information layout](https://drive.google.com/file/d/1_8XG48Z8timFpfSb7P3kl1ZauzUSeYGc/view?usp=sharing)
[3)Sheet5 Realization design focus](https://drive.google.com/file/d/1zGlNXhuhS_bkPF_lhgWrh4I864fhVawl/view?usp=sharing)

=================

2)[Data set : Suicide rates vs prevalence of depressive disorder rates in vizhub](https://vizhub.com/mnalk/701a3a02e67641209795feeeb26c1493)
This dataset help us to answer if depressoin leads to suicide? then what percentage?

[Dataset description:](https://gist.github.com/mnalk/b84ad44d70b8ac709d1cefc01403a683#file-readme-md)
[csv file:](https://gist.github.com/mnalk/b84ad44d70b8ac709d1cefc01403a683#file-suicide_rates_vs_prevalence_of_depressive_disorder_rates-csv)

================

3)[Data set : Prevalence of depression by age in vizhub](https://vizhub.com/mnalk/64d20bde9bfd4b83a84cdcc4c8fa00b8)
This dataset help us to answer Which age group has more depression?

[Dataset description:](https://gist.github.com/mnalk/d869d823ccb0ec67cfaecd3939469e39#file-readme-md)
[csv file:](https://gist.github.com/mnalk/d869d823ccb0ec67cfaecd3939469e39#file-prevalence-of-depression-by-age-csv)

=================

Second, I looked to a more depth dataset with the same goal: why do some countries have more suicides than other countries and why?. Then I updated the dataset to include world development indicators: GDP (current US$) by country:1985 to 2016. Retrieved from [source](http://databank.worldbank.org/data/source/world-development-indicators#).

This indicator would help us to improve tasks and questions regarding suicide among countries. For example, if suicide is high in one country, we would like to know if this is related to low GDP for that specific country.[Readme](https://gist.github.com/mnalk/9774fb9b221cfad2d21c387ff2e417ca#file-readme-md),and [csv file](
https://gist.githubusercontent.com/mnalk/9774fb9b221cfad2d21c387ff2e417ca/raw/feb0bb276f8606781d781a3af18a6e32e3fc418e/Suicide_Rates.csv) explain the new features.


I’ve created a proof of concept visualization of this data. It's a suicide rates visualization and it shows suicide rates among the countries differ widely. Russian seems the highest among other countries, and we can see that Russia only has 22338 suicides number. Unfortunately, we can't tell which gender committed suicides in this visualization and which year in specific.
For example, it would be helpful to capture that male gender numbers who committed suicides in Russia were 22338 in 1994. This would help researchers find out other factors that affected males in particular in 1994.


[![image](https://user-images.githubusercontent.com/70254281/134232441-34cf632a-9233-4227-b8d6-7a84c44f8ddd.GIF)](https://vizhub.com/mnalk/86cf45b181914194852f165c5146c597)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

1)How many people are suicide in each country?
2)Which age group has more suicide rates?
3)Does low GDP per capita leads to suicide? What percentage? .Note(GDP per capita is calculated using a country's GDP in 2012 United States dollars (USD) which is then divided by the country's total population.)
4)Who is more tend to suicide, male or female? .Note(Statistics. The incidence of completed suicide is vastly higher among males than females among all age groups in most of the world. As of 2015, almost two-thirds of worldwide suicides (representing about 1.5% of all deaths) are by men.)
5)Is there any correlation between males who are suicide and GDP per capita for a specific country?


## Sketches


![image](https://user-images.githubusercontent.com/70254281/134373006-83e46552-e38d-4bed-a7e7-fdc8f625cf44.jpeg)

1- Selesct the year then select age grpup. 
2-Zoom and pan on the map.
3- Find out the suicides rate on female/male and the GDP.

## Open Questions
1)I don’t know how to resolve the Y axis due to the large number of countries per year. For example, the USA has data from 1985 to 2015? (30 years of suicide rate)?
2)I don't know if I should resize something like the bar itself or the font size? I still working on this part.
3)I don't know with a large dataset should I change the color for each bar? but the question is how many colores are enough?
