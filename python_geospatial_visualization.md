# Python: geospatial data visualization project guide

Xuechun Yuan

## Introduction

In this tutorial, we will go through the whole process of visualizing geospatial data with Python, starting from getting needed data. The audience would be guided through every step in the process in the context of a real geospatial analysis project.

The data used in this tutorial is the customer data of the Olist store (source: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), which is the largest online store in the Brazilian market. The goal of this sample geospatial analysis project is to visualize the customer data over the Brazilian map in order to gain insights about its customer distribution in differnt geographical regions. Shape files of Brazil states (source: http://diva-gis.org/datadown) and a dataset containing the Brazillian state codes (source: https://github.com/datasets-br/state-codes/blob/master/data/br-state-codes.csv) are used in this tutorial as well.

More detailed information about the used data can be viewed in their respective source link.


### Motivation for the tutorial

This tutorial is motivated by my previous experience in dealing with geojspatial data. Geospatial analysis is an interesting subject that can help bring extremely useful information in many fields and the produced graphs are often eye-catching and intriguing. Our course has just covered this topic in R; meanwhile, another frequently used tool for geospatial analysis would be Python. However, according to my past experience, the tutorials available for the relevant Python packages are not very handy; they usually focus on demonstrating methods for plotting different types of graphs, while in reality we will come across problems well before we are ready to plot the graphs. To name a few:

- Visualizing geospatial data in Python would require us to use a new data structure called "GeoDataFrame", which would contain a new data type called "geometry".


- Typically the needed information for plotting a geospatial graph would rest in more than one dataset, so we need to be skilled at merging all needed datasets while maintaining the validity of the data.


- Some types of graph will require the data to be aggregated.


- ...


Such problems are usually not addressed by the available tutorials for the relevant Python packages. Therefore, I created this tutorial in an attempt to address these problems and help the audience's geospatial data visualization project in Python go smoother.

In addition, available tutorials often do not provide enough systematic knowledge for geospatial data visualization in Python. This tutorial also tries to fill in that gap.


### The need to be addressed

- Introducing requried packages


- Introducing the audience to the new data structure required


- Guide the audience through data preprocessing


- Give some tips and exmaples about the use of different graphing methods


### Own evaluation of the project

I have consolidated my knowledge about the whole process of graphing geospatial data with Python and brushed up on many important points that are easy to miss. Next time, I could improve by including more plot types and going deeper in different details suching as introducing available color schemes choices and modifying the legends.

The tutorial can be found here: https://github.com/xy2506/python_geospatial_visualization
