# Testing


```r
library(gganimate)
library(ggplot2)
anim <- ggplot(iris, aes(Sepal.Width, Petal.Width)) +
geom_point(color = "red") +
  labs(title = "{closest_state}") +
  transition_states(Species, transition_length = 3, state_length = 1)
animate(anim)
```

<img src="sandbox_files/figure-html/unnamed-chunk-1-1.gif" style="display: block; margin: auto;" />


```r
anim<-ggplot(iris,aes(Petal.Width,Petal.Length,colour=Species)) +
  geom_point() +
  transition_filter(transition_length=2, filter_length = 1,Setosa=Species=='setosa',Long = Petal.Length>4,Wide = Petal.Width>2)
animate(anim)
```

<img src="sandbox_files/figure-html/unnamed-chunk-2-1.gif" style="display: block; margin: auto;" />
