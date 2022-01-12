---
title: Test post
author: Callum Savage
date: '2022-01-13'
slug: [what's a slug]
categories: [explorative]
tags: ["ecological forecating", "plotting"]
---

This is a test post


```r
head(iris)
```

```
##   Sepal.Length Sepal.Width Petal.Length Petal.Width Species
## 1          5.1         3.5          1.4         0.2  setosa
## 2          4.9         3.0          1.4         0.2  setosa
## 3          4.7         3.2          1.3         0.2  setosa
## 4          4.6         3.1          1.5         0.2  setosa
## 5          5.0         3.6          1.4         0.2  setosa
## 6          5.4         3.9          1.7         0.4  setosa
```


```r
library(ggplot2)

iris |>
  ggplot(aes(x = Sepal.Length, y = Sepal.Width, colour = Petal.Length)) +
  geom_point()
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-2-1.png" width="672" />

