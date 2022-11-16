# An Interactive Dashboard: COVID-19 Visualization with Shiny and Plotly

Ning Kang

I created the dashboard with Shiny and made the interactive plots with ggplot2 and Plotly. Users can choose from two geography levels: state or region. Users will be prompted to choose one or multiple regions among all eleven regions if the region is selected. Users can also decide the number of variables to visualize. If multiple variables are chosen, a facet grid plot will be displayed. There is a slider to change the date range, which will change the plot accordingly.

Here is the link to the interactive dashboard: [COVID-19 Interactive Dashboard](https://lexkdev.shinyapps.io/cc22/){target="_blank"}

## Motivation for the Project

For the community contribution, I made a dashboard to visualize New York State's Covid-19 testing from 2020-03-01 to 2022-11-13. The pandemic has significantly shaped the past three years, and many things have changed since 2020. Policies have changed compared to 2020, and I wondered by what degree the number/percentage of people being tested positive changed and different regions differed. The data source, New York State Health Data, enables users to visualize the data with Tableau. However, many of the commands are not very intuitive. Also, there are few interactive options available in R libraries regarding multiple selections and filters on data. I built an easier-to-use interactive visualization dashboard, where checking boxes and selecting from dropdowns yields informative plots.

## Evaluation of the Project

Shiny is an intuitive framework for building web applications with R syntax, and knowledge of HTML, CSS, and JavaScript is not required. It is powerful yet easy to learn. I hadn't used Shiny before this project. After reading through the tutorials and sample projects and practicing, I learned about its structure, unique reactivity, and its resemblance and differences to traditional web development tools. I implemented Plotly to add interactivity to the plots, enabling tooltips and zooming in and out.

Users can choose from two geography levels: state or region. Users will be prompted to choose one or multiple regions among all eleven regions if the region is selected. Users can also decide the number of variables to visualize. If multiple variables are chosen, a facet grid plot will be displayed. There is a slider to change the date range, which will change the plot accordingly.

If I were to do this project a second time, I would consider adding cleograph maps. I would add more options for the sidebar panel for other graphs, such as side-to-side bar charts. I would also utilize self-created functions and improve efficiency. Since the data is updated daily, web scrapping could also be used to keep the plot updated.

## References

1.  Data source: <https://health.data.ny.gov/Health/New-York-State-Statewide-COVID-19-Testing/xdss-u53e>

2.  <https://shiny.rstudio.com/tutorial/written-tutorial/lesson1/>

3.  <https://mastering-shiny.org/index.html>
