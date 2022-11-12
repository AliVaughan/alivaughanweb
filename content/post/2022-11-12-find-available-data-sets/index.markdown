---
title: Find available data sets
author: Ali Vaughan
date: '2022-11-12'
slug: [post]
categories: [notes to myself]
tags: [datasets, codesnips]
---

R has a load of inbuilt data sets and you can find them using:


```r
data(package = .packages(all.available = TRUE))
```

This will list the data sets in all available packages.
