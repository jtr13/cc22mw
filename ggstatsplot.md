# Cheatsheet of ggstatsplot in R

Shaonan Wang, Baochan Jiang

This cheatsheet is for ggstatsplot. Use the link to check the cheatsheet:
https://github.com/anna-shaonanw/ggstatsplot-cheatsheet/blob/main/ggstatsplot-cheatsheet.pdf

When we do data analysis, we usually need to visualize the basic situation of the data, including mean, median, mode, etc. Based on this, we will also test and analyze the distribution of the data to understand whether the data presents a normal distribution. If there are two groups of data, we also need to perform a t-test to detect the correlation of the data. And sometimes build a model between data, perform ANOVA test to learn about the model. 

{ggplot} is a good tool to do visualization. However, if you want to display more statistical results in the graph, this will be a very complicated process. You have to perform statistical calculations, and then use {ggplot} to draw the results one by one. In this case, we found a more convenient R package {ggstatsplot} for visualization and display of statistical results.

{ggstatsplot} is an extension of {ggplot2} package for creating graphics with details from statistical tests. It can easily add statistical tests to graphs, support multiple tests, and display P value and other statistical indicators among data subsets in graphs. 

{ggstatsplot} = "data visualization" + "statistical modeling"

In the process of preparing for this cheatsheet, we learned about basic type of plots and multiple statistical approaches and tests. {ggstatsplot} help us make data mining easy and fast. It visually shows the relationship between data sets and the results of statistical tests which helps us better understanding the data, the differences between datasets and statistical tests results of the datasets. 

This package contains more than we have in the cheatsheet, in the next time, we would like to explore more deeply how each parameter in the function contributed to the outcome. And we want to further learn how the group function can show the similarity and difference between multiple data sets, and their relationship.
