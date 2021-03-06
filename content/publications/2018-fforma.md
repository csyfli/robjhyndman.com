---
author: Pablo&nbsp;Montero-Manso, George&nbsp;Athanasopoulos, Rob&nbsp;J&nbsp;Hyndman, Thiyanga&nbsp;S&nbsp;Talagala
date: 2018-10-12
slug: fforma
title: "FFORMA: Feature-based Forecast Model Averaging"
kind: unpublished
tags:
- data science
- time series
- forecasting
file: fforma.pdf
---

We propose an automated method for obtaining weighted forecast combinations using time
series features. The proposed approach involves two phases. First, we use a collection of time series to train a meta-model to assign weights to various possible forecasting methods with the goal of minimizing the average forecasting loss obtained from a weighted forecast combination. The inputs to the meta-model are features extracted from each series. In the second phase, we forecast new series using a weighted forecast combination where the weights are obtained from our previously trained meta-model. Our method outperforms a simple forecast combination, and outperforms all of the most popular individual methods in the time series forecasting literature. The approach achieved second position in the M4 competition.

**Associated R package**: [M4metalearning](https://github.com/robjhyndman/M4metalearning)

