## __Challenge__ 
Use both filter() and select() to create a subset of data frame that contains sepal length of value more than 5, sepal width and species

```R
iris_new= iris %>% filter(Sepal.Length>5) %>% select(Sepal.Width, Species)
```
## __challenge__
Use group_by(), summarize(), mean(), sd(), min(), max() to calculate the mean, standard deviation, get maximum value, minimum value of each Species’ Sepal.Width

```R
grouped_new= iris %>% group_by(Species) %>% summarize(mean_sepal_width = mean(Sepal.Width), Sd_sepal_width= sd(Sepal.Width), max_sepal = max(Sepal.Width), min_sepal= min(Sepal.Width))

```
