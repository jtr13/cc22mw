# (PART) Cheatsheets {-}

# Geographic visualization by ggmap

Yuta Adachi

As my community contribution for the EDAV class, I created a cheat sheet about the geographic visualization by using ggmap.

The link for the cheat sheet is [here](https://github.com/Yuta555/ggmap_cheatsheet/blob/main/ggmap_cheatsheet.pdf).

## Motivation for this project

We sometimes want to describe a fact using geographic visualization. For example, if I'm looking for the shortest path from Columbia University to Central Park, I would like to see a route with a background of road map in which I can understand which street I should walk. However, it seems to be difficult to create a route map or other geographic visualizations by only the original ggplot2 packages, as far as I know.

An R package, "ggmap", makes it easy to download and choose various kinds of map tiles such as the Google Maps and Stamen Maps. In addition, you might feel it is easy to plot data since you can deal with the ggplot2 framework you are familiar with.

That's why I'm eager to learn how to use the ggmap package and create the cheat sheet for everyone.

## My own evaluation/Room for improvement

Through creating the cheat sheet, I learned not only how to utilize the ggmap package, but also what type of plots I can choose for the geographic visualization. Specifically, in order to introduce three examples so that readers can learn how to use the package in a practical way, I researched and implemented several types of plots related to the geographic visualization such as a route map and a scatter plot on a map.

Though I learned many things from the project, I can improve this cheat sheet more by adding the examples of other types of data and visualization. For example, I may create another density plot using a continuous variable, and I will also add a flow map to describe transitions between several locations if I have an opportunity to create next time.
