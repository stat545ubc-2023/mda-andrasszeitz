# mda-andrasszeitz

Created October 5, 2023
Last updated October 18, 2023

This is the repository of Andras Szeitz, Ph.D. student in the GSAT program.
This is the project of UBC STAT 545A course between September and October 2023.
This repository contains the completed project Mini Data Analysis Project: Milestone 1, and Milestone 2.
During Mini Data Analysis Project: Milestone 1, I worked with a dataset 'cancer_samples'. I selected four cancer parameters, i.e., radius_mean, area_mean, smoothness_mean, compactness_mean from this group, and aimed to identify an ideal parameter that can be used to follow cancer growth and status.

Cancer tissue growth samples emit volatile organic compounds (VOCs) that can be analyzed with analytical chemistry techniques and used as biomarkers for diagnosis. I proposed that after tumor diagnosis with such analytical test, cancer growth and status can be followed using the measurement of an ideal cancer parameter, such as cancer radius.
I created several histograms, scatter and box plots, and modified tables to determine which of the several cancer parameters can be used to track cancer development.

After all the data analysis, I propose cancer radius as the ideal cancer parameter to follow cancer growth and status.
During Mini Data Analysis Project: Milestone 2, using ‘radius_mean’ dataset, I processed and summarized my values by combining them with various graphical visualization techniques for quick overview. With the focus of using R packages, such as tidyverse, dplyr, ggplot2, I made sure that my data were tidy and carried out some experiments with making them untidy and back to tidy again. Using selected parameters from the ‘cancer_sample’ dataset, I created linear regression models, obtained the correlation parameters, and used t-test to determine significance between selected variables with the p-value. I performed several data manipulation to predict, for example, Y-values, determine regression line bias (%) of the datapoints, and tidied up my data with the broom function. Finally, I checked the robustness and reproducibility of my RDM files by relocating them on my PC and operating the files from the new location and deleting csv files and re-making them by knitting the RDM file. This process was also repeated with R binary RDS files.


