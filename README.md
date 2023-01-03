# Mapping Individual Semantic Spaces using the Demonstrative Choice Task

Here you find the accompanying code for the for my **Bachelor thesis** in the autumn of 2022 at the University of Aarhus.

## Project Description

The aim of the project was to investegate whether demonstratives (this/that) could be used to probe individual differences in personality.
Most of the preprocessing, wrangling and plots are conducted in R.
The bulk of the analysis is conducted in Python using scikit-learn.

## Repository Structure

* The project report can be found as: *thesis.pdf*
* Code can be found in the folder: *Code/*
* Figures can be found in: *Code/figures/*
* Data can be found in: *Code/Data/*
* The Latex script can be found as: *main.tex*
* The literature can be found as BibTex: literature.bib

## Scripts

Here is a list of which scripts are used for which steps of the analysis:

* Preprocessing: *preprocessing.Rmd*
* Summary Statistics: *preprocessing.Rmd* and *group_summary_stats.Rmd*
* Factor analysis: *factor_analysis.Rmd*
* Mapping differences between semantic landscapes of healthy individuals and individuals with depression/anxiety: *lexicon_analysis.Rmd*, *lexicon_analysis.ipynb*, and *lexicon_analysis_VIF.ipynb*
* Using demonstratives to predict depression and anxiety: *words_as_predictors.Rmd*, *words_as_predictors.ipynb*, and *words_as_predictors_VIF_ipynb*
* Miscellaneous: *misc.Rmd*

## Software Prerequisites

Running the code for the project requires R and Python. 
RStudio and Jupyter Notebook were used as IDE's. 


