# DataExplorer Cheatsheet, EDA made easier

Ryan McNamara and Matthieu Schulz

As our community contribution, we created a cheat sheet about the DataExplorer package that automates the process of EDA.
[our cheatsheet can be found here](resources/data_explorer_cheatsheet/data_explorer_cheat_sheet.pdf){target="_blank"}

## Motivation for the contribution

Exploratory data analysis, or EDA, is the initial necessary step in diagnosing any dataset that one plans to work on. EDA can be used as a standalone practice to explore a dataset and report any observations/hypotheses, or it can be used as a precursor to the application of ML algorithms. In either case, it is crucial to explore one’s data before drawing any conclusions. Common examples of EDA, which are often repeated, include: visualizing variable distributions, exploring the relationships between variables, documenting missing values, etc. Many of these explorations are done using graphs/charts such as histograms, box plots, and scatter plots. While EDA is a vital part of data analysis/predictive modeling, it is often tedious to write the repetitive code required to make such visualizations.

An R package, DataExplorer, automates the process of EDA and makes it much simpler and faster to produce exploratory visuals. The package is easy to learn and is a great tool for any data scientist looking to speed up their analyses. While there are a few online tutorials explaining the basics of DataExplorer, we were unable to find any resource that allows for quick referencing of the package’s different functions. Thus, we decided to construct a cheat sheet for DataExplorer as our Community Contribution. We believe our convenient cheat sheet will make it easy for anyone to familiarize themselves with the package and quickly reference the capabilities of the package. 

## Evaluation of DataExplorer and learnings

While creating this cheat sheet we learned a lot about the power of the DataExplorer package. We have seen how to quickly create figures that will give us an overview of our dataset using the many plotting functions available. The most useful function of the DataExplorer package is the create_report function, which will compile an HTML report of the plots available through the package. This single function gives the user a complete overview of the dataset they are working with, including information about distributions, missing values, and correlations. The DataExplorer package essentially performs EDA for the user, expediting the process of exploring one’s data. We will certainly be using the create_report function for any data-driven project we work on in the future. 

We also learned a lot about the data.table data structure while working on this assignment. We have been using the data.frame data structure throughout the semester, however, the DataExplorer package is designed to work with data.table. The data.table has a few advantages over the data.frame, including speed and the ability to rename columns, group by columns, and sort by columns directly within the data.table syntax. We are interested in learning more about the data.table and will use it in our code moving forward. 

If we had to do this project again, we would start by exploring the data.table package in more depth. The DataExplorer package works with data.frames as well, however, it is designed to work with data.tables (the data.table will be updated in place while the data.frame will not). Given the advantages the data.table has over the data.frame, it is worth learning and becoming familiar with. We also would create our cheat sheet using a different software than Google Docs/PowerPoint because it was somewhat difficult to create drawings/images. If we were to create another cheat sheet (i.e. for the data.table package), we would create it using Adobe Illustrator or a similar application. Overall, we learned a lot through the creation of our cheat sheet and hope that others find value in it as well. 

## Sources: 
https://cran.r-project.org/web/packages/data.table/vignettes/datatable-intro.html
https://cran.r-project.org/web/packages/DataExplorer/DataExplorer.pdf 

