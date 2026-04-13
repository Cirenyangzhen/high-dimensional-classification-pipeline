# High-Dimensional Classification Pipeline in R

An end-to-end machine learning project for a high-dimensional grouped classification task, built with R and tidymodels.

## Project Overview

This project develops a predictive pipeline for a challenging classification problem with three key characteristics:

* high dimensionality
* grouped observations
* missing data / preprocessing requirements

A major modelling constraint is that observations belonging to the same group must remain together during data splitting and cross-validation to avoid data leakage.

The workflow includes exploratory data analysis, preprocessing, grouped cross-validation, baseline modelling, model comparison, hyperparameter tuning, threshold optimisation, and final holdout prediction.

## Tech Stack

* R
* tidyverse
* tidymodels
* recipes
* parsnip
* bonsai
* themis

## Key Results

* Dataset size: 7,403 observations, 390 variables, 385 feature columns, 550 groups
* Baseline Logistic Regression CV F1: 0.7281
* Tuned Random Forest CV F1: 0.7703
* Final improvement over baseline: +0.0422 F1

## Repository Contents

* `Task02.Rmd` — source analysis and modelling pipeline
* `Task02.pdf` — knitted coursework report
* `mypreds.rds` — final predictions on holdout data

## Notes

This repository is based on postgraduate coursework and has been reorganised as a portfolio project to highlight practical skills in high-dimensional data analysis, grouped validation, and supervised learning.
