# intern_team_8_2022_Extreme_Events

This repository contains notebook and material for extreme value analysis (EVA). We will be using **pyextreme** package which contains all the necessary tools and algorithms for EVA. The obejctive of this project is to use EVA to build a statistical model that outputs the probability of an extreme event occuring within a specified time frame. There are two methods we will be employing: the Block Maxima and Peak Over Threshold. Each method extracts extreme values from the time series data, and uses the extracted data to fit a some distribution. 

**pyextremes** is a Python library aimed at performing univariate Extreme Value Analysis (EVA). It provides tools necessary to perform a wide range of tasks required to perform EVA, such as:

* extraction of extreme events from time series using methods such as Block Maxima (BM) or Peaks Over Threshold (POT)
* fitting continuous distributions, such as GEVD, GPD, or user-specified continous distributions to the extracted extreme events
* visualization of model inputs, results, and goodness-of-fit statistics
* estimation of extreme events of given probability or return period (e.g. 100-year event) and of corresponding confidence intervals
* tools assisting with model selection and tuning, such as selection of block size in BM and threshold in POT

The dataset used is from the NOAA (https://tidesandcurrents.noaa.gov/waterlevels.html?id=8518750). The website provides climatology data which are recorded from different stations across the US. The dataset contains water level elevation from different periods of time. The data is extracted and stored in a database for easy access and storage. 

Estimators and analysis for extreme value theory (EVT). The package is structured as follows:

* The POT method.
  * Plot the tail.
  * QQ-plot against exponential.
  * Zipf-plot.

* Estimators: calculate estimates and [confidence intervals]. Plotting routines for analysis.
   * [Hill estimator](https://github.com/spmvg/evt/blob/master/tutorial/3_hill_estimator_and_the_estimate_object.ipynb).
     Plot against order statistics.
   * [Moment estimator](https://github.com/spmvg/evt/blob/master/tutorial/4_moment_estimator.ipynb) (Dekkers-Einmahl-De Haan).
     Plot against order statistics.
   * [Maximum likelihood for the generalized Pareto distribution]

 Plot fit quality.
   * [Maximum likelihood for the generalized extreme value distribution]
     Plot fit quality.
     
     
     
 Installation
 ------------
 Releases are made available on PyPi.
 The recommended installation method is via `pip`:

 ```python
 pip install pyextreme 
 
 
