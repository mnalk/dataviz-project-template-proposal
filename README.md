
# Data visualization project name: suicide prevention visualization project

## Data

The data I propose is to visualize for suicide prevention dataset that pulled from four other datasets linked by year and country and was built to find signals correlated to increased suicide rates among different cohorts globally, across the socio-economic spectrum.

References United Nations Development Program. (2018). Human development index (HDI). Retrieved from [source](http://hdr.undp.org/en/indicators/137506)

World Bank (2018). World development indicators: GDP (current US$) by country:1985 to 2016. Retrieved from [source](http://databank.worldbank.org/data/source/world-development-indicators#)(2017). Suicide in the Twenty-First Century [dataset]. Retrieved from [source](https://www.kaggle.com/szamil/suicide-in-the-twenty-first-century/notebook)

World Health Organization. (2018). Suicide prevention. Retrieved from [source](http://www.who.int/mental_health/suicide-prevention/en/)

[Inspiration Suicide Prevention](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016?select=master.csv)

## Prototypes

First, I studied the suicide concept, and then I reviewed several sources to learn which attributes are more important than others.

Here are my attempts to understand the suicide consent :

1)[data set: Number with depression by country in vizhub](https://vizhub.com/mnalk/e116a887f76a43fbb5d0025e4e30b7aa)
This data set helps to understand how many people in each year have depression? 

[Dataset description:](https://gist.github.com/mnalk/55e775e87b4232179fdd45a1db9ec129#file-readme-md)
[csv file:](https://gist.github.com/mnalk/55e775e87b4232179fdd45a1db9ec129#file-number-with-depression-by-country-csv)

Sketch for dataset(Number with depression by country)was a process to create ideas below. The methodology used is [five design sheet](http://fds.design/)

[1)Sheet1 brain storm Ideas, Filter, Categorize, Combine/Refine, Question](https://drive.google.com/file/d/1NCOTkhhsna9SWYfg8CBFj2H690CpC4hv/view?usp=sharing)
[2)detailed information layout](https://drive.google.com/file/d/1_8XG48Z8timFpfSb7P3kl1ZauzUSeYGc/view?usp=sharing)
[3)Sheet5 Realization design focus](https://drive.google.com/file/d/1zGlNXhuhS_bkPF_lhgWrh4I864fhVawl/view?usp=sharing)

=================

2)[data set : Suicide rates vs prevalence of depressive disorder rates in vizhub](https://vizhub.com/mnalk/12565fba83094a0da620f44c933912ac)
This dataset helps us to answer how many people in specific years have suicided per 100000 individuals? 

[Dataset description:](https://gist.github.com/mnalk/b84ad44d70b8ac709d1cefc01403a683#file-readme-md)
[csv file:](https://gist.github.com/mnalk/b84ad44d70b8ac709d1cefc01403a683#file-suicide_rates_vs_prevalence_of_depressive_disorder_rates-csv)

================

3)[data set : Prevalence of depression by age in vizhub](https://vizhub.com/mnalk/e0665cc83fa34b4eac18031abb66f77e)
This dataset helps us answer which year is the prevalence of depression age (20 to 24 years old). We are more concerned about young people's suicide rates in this question.

[Dataset description:](https://gist.github.com/mnalk/d869d823ccb0ec67cfaecd3939469e39#file-readme-md)
[csv file:](https://gist.github.com/mnalk/d869d823ccb0ec67cfaecd3939469e39#file-prevalence-of-depression-by-age-csv)

=================

Second, I looked to a more depth dataset with the same goal: why do some countries have more suicides than other countries and why?. Then I updated the dataset to include world development indicators: GDP (current US$) by country:1985 to 2016. Retrieved from [source](http://databank.worldbank.org/data/source/world-development-indicators#).

This indicator would help us to improve tasks and questions regarding suicide among countries. For example, if suicide is high in one country, we would like to know if this is related to low GDP for that specific country.[Readme](https://gist.github.com/mnalk/9774fb9b221cfad2d21c387ff2e417ca#file-readme-md),and [csv file](
https://gist.githubusercontent.com/mnalk/9774fb9b221cfad2d21c387ff2e417ca/raw/feb0bb276f8606781d781a3af18a6e32e3fc418e/Suicide_Rates.csv) explains the new features.


I've created a proof of concept visualization of this data. It's a suicide rates visualization, and it shows that suicide rates among the countries differ widely. For example, Russian seems the highest among other countries, and we can see that Russia only has 22338 suicides number. Unfortunately, we cannot tell which gender committed suicides in this visualization and which year in specific.
For example, it would be helpful to capture that male gender numbers who committed suicides in Russia were 22338 in 1994. This would help researchers find out other factors that affected males in particular in 1994.


## Questions & Tasks
The following tasks and questions will drive the visualization and interaction decisions for this project:

* How many people are suicide in each country on the map?
* Which age group has more suicide rates on the map?
* Does low GDP per capita leads to suicide? What percentage?
-Note(GDP per capita is calculated using a country's GDP in 2012 United States dollars (USD) which is then divided by the country's total population.)
* Who is more tend to suicide, male or female? 
-Note(The incidence of completed suicide is vastly higher among males than females among all age groups in most of the world. As of 2015, almost two-thirds of worldwide suicides (representing about 1.5% of all deaths) are by men.)
* Is there any correlation between males who are suicide and GDP per capita for a specific country?

## Sketches
![image](https://user-images.githubusercontent.com/70254281/134373006-83e46552-e38d-4bed-a7e7-fdc8f625cf44.jpeg)

#Prototype 1
[![image](https://user-images.githubusercontent.com/70254281/137199180-dba65b29-3646-40b8-8a71-524d6ef49077.GIF)](https://vizhub.com/mnalk/761c8d9681ae455c96ab92813271431b)
#Prototype 2
[![image](https://user-images.githubusercontent.com/70254281/137198347-841f1f3c-23c4-4e83-b296-b1468d344218.png)](https://vizhub.com/mnalk/d9ce801e7d6a4e16a5c67cbe501f883e)
#Prototype 3
[![image](https://user-images.githubusercontent.com/70254281/134232441-34cf632a-9233-4227-b8d6-7a84c44f8ddd.GIF)](https://vizhub.com/mnalk/86cf45b181914194852f165c5146c597)


* Select the year, then select age groups by using dropdown menus.
* Zoom and pan on the map.
* Find out the suicides rate for females/males and the GDP in each country.

## Open Questions
* I do not know how to resolve the appearance of one country per multiples years. For example, the USA has data from 1985 to 2015, which means 30 years of suicide rate.
* I do not know if I should resize something like the bar itself or the font size? I am still working on this part.
* I do not know with a large dataset, should I change the color for each bar? However, the question is, how many colors can humans preserve?

## Schedule of Deliverables
* Task 1: (Templet) of the map was inspired from [Migrant Deaths over Time](https://bl.ocks.org/curran/raw/a479b91bba14d633487e/?raw=true). I use this as a base to work on JSON files and related files as well. Then push to Github. This part is Done.
* Task 2: I will work on dropdown menus to select ages dropdown menus 1: example age group 1: 20 -25. dropdown menu 2:  yers example year 1995. Time estimate: 2 weeks
* Task 3: Tooltip guideline. For example, icons for females and males, also icons for high/low GDP: Time estimate: 2 weeks
* Task 4: Add colors, and refine the whole project. Time estimate: 2 weeks

## Iterated work 
[![image](https://user-images.githubusercontent.com/70254281/138611502-7c706de6-842f-4a15-892e-07e38b4e5a27.GIF)](https://mnalk.github.io/vis/index.html).

In this version, 10/27/2021 , I noticed that the two dropdown means creating issues, so I would work on this part to improve the dropdown menu interaction. I also want to try how brushing works on the map by selecting one or more data points,and I think it's worth trying it out. 

Brushing map on vishub :
[![image](https://user-images.githubusercontent.com/70254281/139157190-f3ae9573-2708-43d9-bf4f-2f19e425c03c.GIF)](https://vizhub.com/mnalk/df74a298d1ec4af78f39f52a657a0853).

## Notebook : 
[notebook_Suicide_Rates](https://github.com/mnalk/notebook_Suicide_Rates)

Work on your project itreation :
[![image](https://user-images.githubusercontent.com/70254281/140659774-68f36833-cbe8-4cec-9f1d-5b31baf1a4fe.png)](https://vizhub.com/mnalk/ee8312b21b714a7e93e02abb3a182536?file=README.md).

A demonstration of how to bulid a heatmap with mouseover, and mouseleave behaviour in 3 distinct functions. The square style is slightly modified when the element is hovered. It allows to make more obvious which element is observed. In this exmple I used only subset of the dataset as follow:

Japan Mexico Brazil Argentina Philippines Russia Turkey France .Then, I represent male and female suicide rates.

## Iterated work  11/17/2021

[![image](https://user-images.githubusercontent.com/70254281/142287239-3cbcbd7a-4665-4016-bbf9-12461143caf4.png)](https://vizhub.com/mnalk/275285a786384534b21a15445fdb1179).

In this version I use [Tippy.js](https://atomiks.github.io/tippyjs/v6/getting-started/) and [Tippy.js for React](https://github.com/atomiks/tippyjs-react/) to add tooltip which integrates well with React. I created  my own theme called suicide to apply it for some part of the visulazation.


## Iterated work  12/01/2021

[![image](https://user-images.githubusercontent.com/70254281/143970829-fa9f23e8-8311-4ebe-81bc-104cc625bbd6.png)](https://vizhub.com/mnalk/76426e87c1994e7dad27a64c93c4a417?edit=files&file=index.html&mode=mini).



## Iterated work  12/01/2021
My goal is to combine dashboards 1 and 2. Basically, I want to add the map to be the third component on my dashboard.

[![image](https://user-images.githubusercontent.com/70254281/144258939-d05b389f-0996-4ec2-8e65-a3ecc8e87cd4.GIF)](https://vizhub.com/mnalk/de0a187e6f8f4ea7a14f5cb69a7089ed).

## Final project  12/08/2021

[![image](https://user-images.githubusercontent.com/70254281/144796127-6516d720-5ea0-442e-b5d7-3bc380c11afe.png)](https://vizhub.com/mnalk/76426e87c1994e7dad27a64c93c4a417?edit=files&file=index.html&mode=mini).
[Dashboard demo:](https://mnalk.github.io/Final_Dashboard/)
[csv file:](https://gist.github.com/mnalk/d869d823ccb0ec67cfaecd3939469e39#file-prevalence-of-depression-by-age-csv)

