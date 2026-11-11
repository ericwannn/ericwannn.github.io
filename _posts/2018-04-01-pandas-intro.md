---
layout: post
title: "Intro to Pandas"
date: 2018-04-01 00:00:00 +0800
categories: ["Data engineering"]
tags: ["machine learning", "data engineering"]
---

# Data pre-processing

- Threshold values into 0/1

~~~python
import pandas as pd

a = pd.Series([1,3,5,6,3,4,1,2,0,4])
b = Series(a>3).astype(int)
print(b)
~~~
