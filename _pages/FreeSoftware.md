---
layout: archive
title: "Open-Source Software"
permalink: /FreeSoftware/
author_profile: true
---

Below are the 3 R packages that I developed as a fun side project during my Master's degree.

In addition, I'm happy to have contributed to **scikit-learn** ([v1.9](https://scikit-learn.org/stable/whats_new/v1.9.html){:target="_blank"}, June 2026) as well with [this](https://github.com/scikit-learn/scikit-learn/pull/33014){:target="_blank"} merged pull request. This PR resolved a conflict in initialization logic for the core elastic net optimization engine (coordinate descent path, known as enet_path).

R package `powerplus` (3.1) [Dorador, A. (2016)]
------
- What: Computation of matrix and scalar exponentiation -- any base, any exponent (yes, even complex)

- Why: I wanted to have arbitrary row/column resolution in biplots, which relies on being able to raise a matrix to an arbitrary power within the unit interval.

- Where: Formerly on CRAN. Perfectly working archived versions are available to download [*here*](https://cran.r-project.org/src/contrib/Archive/powerplus/){:target="_blank"} for free.

- Number of downloads as at Aug 17, 2026: 33,390


R package `complexplus` (2.1) [Dorador, A. and Thygesen, U.H. (2016)]
------
- What: Extension of several functions to the complex domain, including the matrix exponential and logarithm, and the determinant.

- Why: Serve as general-purpose helper functions, which come in handy e.g. in matrix and scalar exponentiation (behind the scenes).

- Where: Formerly on CRAN. Perfectly working archived versions are available to download [*here*](https://cran.r-project.org/src/contrib/Archive/complexplus/){:target="_blank"} for free.

- Number of downloads as at Aug 17, 2026: 49,976


R package `analytics` (3.0) [Dorador, A. (2017)]
------
- What: Regression Outlier Detection, Stationary Bootstrap, Testing Weak Stationarity, Missing Value Imputation, and Other Tools for Data Analysis

- Why: There weren't any user-friendly functions (or any at all) to compute those quantities, which I needed for my Master thesis.

- Where: Formerly on CRAN. Perfectly working archived versions are available to download [*here*](https://cran.r-project.org/src/contrib/Archive/analytics/){:target="_blank"} for free.

- Number of downloads as at Aug 17, 2026: 19,776

