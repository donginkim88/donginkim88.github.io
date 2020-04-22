--- 
layout: post
title: "Generating a Toy Dataset" 
category: Analytics 
---

One of the things boggled me when first started learning a data science was to find proper data sets to test out my algorithm (It was a lot more difficult those days).

Later on, I found multiple useful websites and api where they provide bunch of datasets just ready for ML, but still it is good to know how to create a handy, simple dataset and test out with it before we do anything more complex.


```
mu = 10
sigma = 5

sigma * np.random.randn(100, 2) + mu
```
