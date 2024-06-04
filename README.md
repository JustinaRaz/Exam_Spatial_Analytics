# Examining the Patterns of Foreign Migration to Denmark

## Short description

The repository was created to store the contents of the exam project for the *Spatial Analytics* (spring, 2024) course in *Aarhus University*. This repository contains code and other files that are required to reproduce the plots and results which are discussed in the project.

The main goal of this exam project was to explore immigration patterns to Denmark during the time period of 2020-2023. Spatial Autocorrelation analysis - *Moran's I test with Monte Carlo Simulations* - was performed to investigate whether the total numbers of newcomers with the same country of origin tend to cluster across municipalities of Denmark.

## Structure of the repository

An overview of files:

| File  | Explanation |
| ------------- | ------------- |
| Exam_plots_analysis.Rmd  | Contains code for plotting the figures, and performing the analysis of Spatial Autocorrelation. This file is included in "Spatial_Analytics.zip".|
| Spatial_Analytics.zip  | Once unzipped, it will contain 3 folders: "data", "plots" and "RMD". "Data" folder contains data, which was used in preprocessing and analysis. "Plots" folder will be empty, but these can be generated after running RMDs, located in the folder "RMD". |
| data.zip  | The same folder containg data as in "Spatial_Analytics.zip". The purpose of including this way was to allow people download the data only.|
| plots.zip  | Contains all of the plots generated during the analysis.|
| preprocessing_data.Rmd  | Contains the code for preprocessing of the data. This file is included in "Spatial_Analytics.zip".|

## To reproduce the analysis

In order to reproduce the analysis, you can clone the repository by opening the terminal and running the following:

```
git clone https://github.com/JustinaRaz/Exam_Spatial_Analytics.git
```
Before doing so, make sure to set the directory of where the repository should be cloned to.

Then:

1. Unzip the folders that are currently zipped.
2. Open R Studio, and set the working directory to the folder called "Spatial_Analytics".
3. Open both .Rmd files, located in "RMD" folder.
4. Run the code chunks.

## Contacts

If you have any questions, reach out to 202109601@post.au.dk.
