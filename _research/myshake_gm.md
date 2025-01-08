---
title: "Studying Earthquake Ground Motion using Crowdsourced Smartphone Records"
excerpt: "Building and deploying a ground motion model using MyShake records <br/><img src='/images/myshake_gmm_event_plot.png'>"
collection: projects
---

The MyShake smartphone app is known for delivering earthquake early warning messages to users on the US West Coast. However, it also crowdsources triggered acceleration waveforms using the onboard accelerometer. These waveforms are collected from densely distributed MyShake user devices in urban areas, with the potential for building a dense dataset that could aid with the development of next-generation, non-ergodic ground motion models (GMMs), that incorporate the spatial variability in ground motion at high spatial resolution. However, the predictive power of smartphone data for free-field ground motion (i.e. the ground motion not in buildings) has not been evaluated before.

In this work, we assemble a dataset of MyShake ground motion records, and apply ground modeling techniques to identify the factors affecting MyShake-recorded peak accelerations and map any potentially unidentified systematic effects in ground motion. We develop a ground motion model for smartphone-recorded acceleration, and utilize the correlations of MyShake residuals to free-field ground motion residuals to illustrate the predictive power of smartphone data for free-field ground motion. We show a correlation coefficient of 0.4 between free-field residuals for short-period ground-motion metrics and smartphone peak acceleration.

*This work has now been published in BSSA - see the manuscript [here](https://doi.org/10.1785/0120240209)*

![MyShake data and GMM prediction for the M4.5 El Monte earthquake](/images/myshake_gmm_event_plot.png)

*Figure shows MyShake smartphone data for the M4.5 El Monte earthquake in Los Angeles in September 2020. It also shows the median and event-corrected MyShake GMM predictions against epicentral distance.*

![MyShake and free-field within-event residual correlation](/images/free_field_vs_myshake_within_ev_resids_aggregated_pearsonr.png)

*Correlation of MyShake within-event residuals with Peak Ground Acceleration (PGA) and Spectral Acceleration at 0.3 s (SA(0.3s)) free-field within-event residuals, against separation distance.*
