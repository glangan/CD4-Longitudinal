# CD4 Cell Count - Longitudinal Data Analysis

The CD4 dataset contains the CD4 cell count with time for each patient, grouped by their
IDs. Several other variables like age at seroconversion, number of packets of cigarettes smoked
per day, index for depression measured at each time point etc are also included. The dataset
contains 2376 observations collected longitudinally for 369 patients.

In this project, we will explore the variables that effect the CD4 cell count graphically.
Then, some of the preliminary linear models using the selected variables that effect the
CD4 cell count are studied and compared. Further, more models with different covariance
structure and random effects along with the selected fixed effects are considered.

One patient was selected and the estimated covariance and correlation matrix are studied.
Finally, few patients with time evenly divided on either side of Time = 0 are selected. Their
individual trajectories are predicted using the Best Linear Unbiased Estimator (BLUP). The
predictions are plotted alongside each other and the mean predicted response of the CD4 cell
count over time.

[Link to analysis](https://glangan.github.io/CD4-Longitudinal/)