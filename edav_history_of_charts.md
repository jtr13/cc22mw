# History of Charts

Sheris Johnet

## Motivations

For my community contribution, I researched the history of different charts we discussed in class. I discovered when these charts were created and who invented them and the history of these inventors. I was motivated to do this project because I found that knowing the history provided an interesting context to what we were learning and also made it easier to remember what we were learning. Furthermore, because these statisticians had connections to what I had learned in school previously, I thought it would be fascinating to learn about them.

This project addresses the needs of those individuals who want to learn more about the history of charts and see how they slowly evolved. It also shows us how recent some of these discoveries are. Additionally, there are so many resources on more technical aspects of exploratory data analysis, I wanted to provide other resources.

I have learned how to research more thoroughly and be more cautious of the resources I use. For example, for some of the charts there was a contradiction between who created a chart, but this is because of the difference between who coined the chart name and who actually created the chart. I could only find which person did which through more careful research. Next time, I will show more restraint when falling down the rabbit hole of research.

A link to the pdf file, that contains another timeline chart can be seen in resources/edav_history_of_charts/EDAV_CC.



```r
dta <- data.frame(charts = c('Line, Are & Bar Charts','Pie Chart',
                              'Heatmap','Parallel Cooridnate Plot',
                              'Histogram','Biplots','Boxplot','Cleveland Dot Plot','Slope Graph', 'Word Cloud'),
                  year = c(1786,1801,1873,1885,1891,1971,1977,1981,1983,2005))
dta$year <- as.Date(ISOdate(dta$year, 1, 1)) # assuming beginning of year for year 
# str(dta)

library(timelineS)
timelineS(dta, main = "Charts Timeline",label.position = c(1,2))
```

<img src="edav_history_of_charts_files/figure-html/unnamed-chunk-2-1.png" width="80%" style="display: block; margin: auto;" />

## Line, Area & Bar Chart, Pie Chart: William Playfair

-   In 1786, William Playfair invented the line, area and bar chart. In 1801, he also invented the pie chart.

-   He was Scottish and had a vast amount of careers including accountant, economist, translater and silversmith.

-   He was a secret agent for Great Britain during the French Revolutionary Wars in 1793. He spearheaded a plan to make counterfeit assignats (French currency) and then distribute these assignats to France. This eventually caused turmoil with the French government as their currency became worthless.

-   Playfair helped create one of the first modern statistical charts. However, these charts were seen as childish and would not become popular until later. This may be due to the technological difficulties when trying to produce these charts in academic papers.

## Heatmap

-   In 1873, Toussaint Loua used a heatmap to better see the social statistics of districts in Paris. \* In 1991, the software developer Cormac Kinney trademarked the word heatmap but the trademark was not renewed.

## Parallel Coordinate Plot

-   In 1885, Philbert Maurice d'Ocagne is thought to have invented parallel cooridinates. Similarly, Henry Gannetts of 1880 and Henry Gannets of 1898 introduced other methods using parallel cooridinates. However, the visualization techniques we use today by Alfred Inselberg in 1959.

-   Alfred Inselberg was an American-Israeli computer scientist. He worked at IBM where he came up with the mathematical model of the ear.

## Histogram: Karl Pearson

-   Karl Pearson introduced the term histogram in 1891.

-   Albert Einsten read Pearson's book The Grammar of Science in his study group. Many of his ideas presented in this book would influence Einstein.

-   Pearson also created the chi-squared test and the correlation coefficient. He is also of having one of the earliest uses of the mode.

-   Pearson was also a eugenicist.

## Biplots: K Ruben Gabriel

-   Kuno Ruben Gabriel invented the biplot in 1971.

-   He also worked on statistical meterology.

## Boxplot: John Tukey

-   In 1977, Tukey invented the boxplot. In addition, he is credited with inventing the multiple comparison test, Tukey's honest significance test, the five number summary and encouraging the use of exploratory data analysis.

-   Tukey coined the terms software and bit.

-   He worked at AT&T Bell Labs. He also worked with Samuel S Wilks at the math department in Princeton. (Wilks contributed to the development of the Shapiro-Wilks test.)

## Cleveland Dot Plot: William S Cleveland

-   William S Cleveland invented the Cleveland dot plot in 1981.

-   He also worked at AT&T Bell Labs

## Slope Graph: Edward Tufte

-   In 1983, in his book The Visual Display of Quantitative Information Edward Tufte explained what a slope graph is, but the term itself was only coined around 2011.

-   In 2010, he was appointed by President Obama to be in the American Recovery and Reinvestment Act's Recovery Independent Advisory Panel so that there would be transparency in the use of recovery-related funds to provide relief for families in the Great Recession.

-   As a professor in statistics at Yale, he has done much work on how to present information graphics. He criticizes the use of Microsoft Powerpoint due to its simple charts and inadequate default settings and templates.

## Word Cloud: Jonathon Feinberg

-   When he was working on a social bookmarking app at IBM, Jonathon Feinberg invented the word cloud in 2005.

-   In 2008, he also created Wordle.

References:

-   Encyclopædia Britannica, inc. (n.d.). Karl Pearson. Encyclopædia Britannica. Retrieved November 15, 2022, from <https://www.britannica.com/biography/Karl-Pearson>

-   John Tukey - Biography. Maths History. (n.d.). Retrieved November 15, 2022, from <https://mathshistory.st-andrews.ac.uk/Biographies/Tukey/> Kopf, D. (2022, March 20).

-   When did charts become popular? Priceonomics. Retrieved November 15, 2022, from <https://priceonomics.com/when-did-charts-become-popular/#>:\~:text=The%20modern%20statistical%20chart%20was,line%20chart%2C%20and%20pie%20chart. Pluviophile, PluviophilePluviophile 2, & Abdul-Kareem Abdul-RahmanAbdul-Kareem Abdul-Rahman 13655 bronze badges. (1967, October 1).

-   Who invented the "histogram"? Cross Validated. Retrieved November 15, 2022, from <https://stats.stackexchange.com/questions/479735/who-invented-the-histogram>

-   Samuel Wilks - Biography. Maths History. (n.d.). Retrieved November 15, 2022, from <https://mathshistory.st-andrews.ac.uk/Biographies/Wilks/> Scutaru, C. (2019, July 2).

-   History of charts: Who invented this chart type? Data Xtractor. Retrieved November 15, 2022, from <https://data-xtractor.com/blog/data-visualization/chart-history-who-invented-this-chart-type/> Scutaru, C. (2019, July 2).

-   What are heat maps? guide to heatmaps/how to use them. Hotjar. (n.d.). Retrieved November 15, 2022, from <https://www.hotjar.com/heatmaps/>

-   Wikimedia Foundation. (2018, September 27). K. Ruben Gabriel. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/K._Ruben_Gabriel>

-    Wikimedia Foundation. (2020, December 10). Samuel S. Wilks. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/Samuel_S._Wilks>

-   Wikimedia Foundation. (2020, January 8). The grammar of science. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/The_Grammar_of_Science>

-   Wikimedia Foundation. (2022, April 23). Philbert Maurice d'ocagne. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/Philbert_Maurice_d%27Ocagne>

-   Wikimedia Foundation. (2022, August 30). Edward Tufte. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/Edward_Tufte>

-   Wikimedia Foundation. (2022, July 9). Parallel coordinates. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/Parallel_coordinates>

-   Wikimedia Foundation. (2022, October 2). Karl Pearson. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/Karl_Pearson> '

-   Wikimedia Foundation. (2022, October 28). John Tukey. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/John_Tukey>

-   Wikimedia Foundation. (2022, October 3). Histogram. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/Histogram>

-    Wikimedia Foundation. (2022, October 30). American Recovery and Reinvestment Act of 2009. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/American_Recovery_and_Reinvestment_Act_of_2009>

-   Wikimedia Foundation. (2022, September 17). Alfred Inselberg. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/Alfred_Inselberg>

-   Wikimedia Foundation. (2022, September 9). William S. Cleveland. Wikipedia. Retrieved November 15, 2022, from <https://en.wikipedia.org/wiki/William_S._Cleveland>

-   William Playfair founds statistical graphics, and invents the line chart and Bar Chart. William Playfair Founds Statistical Graphics, and Invents the Line Chart and Bar Chart : History of Information. (n.d.). Retrieved November 15, 2022, from <https://www.historyofinformation.com/detail.php?entryid=2929>
