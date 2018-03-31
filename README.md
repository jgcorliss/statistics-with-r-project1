# Exploring Data from the Behavioral Risk Factor Surveillance System

This repository contains my final data analysis project for the Coursera course [Introduction to Probability and Data](https://www.coursera.org/learn/probability-intro), which is Course 1 of 5 in the Statistics with R Specialization. In this project, I investigated novel research questions regarding the 2013 data from the Behavioral Risk Factor Surveillance System (BRFSS). To view the full project including all output and plots, please download the project HTML file and open in a web browser. The repository files are as follows:

* `brfss2013.RData` - Project dataset
* `brfss_codebook.html` - Dataset codebook
* `intro_data_prob_project.Rmd` - Project R Markdown file
* `intro_data_prob_project.html` - **Project HTML file**
* `intro_data_prob_project_rubric.html` - Grading rubric

According to the dataset codebook, the BRFSS is "a collaborative project between all of the states in the United States (US) and participating US territories and the Centers for Disease Control and Prevention (CDC). [...] BRFSS is an ongoing surveillance system designed to measure behavioral risk factors for the non-institutionalized adult population (18 years of age and older) residing in the US. [...] The BRFSS objective is to collect uniform, state-specific data on preventive health practices and risk behaviors that are linked to chronic diseases, injuries, and preventable infectious diseases that affect the adult population."

I identified three research questions that could be answered using this dataset by studying summary statistics and data visualizations in R:

1. *Is increased fruit and vegetable intake associated with improved overall health?* I find that among US adults, greater consumption of fruits and vegetables is associated with improvements in perceived overall health.
2. *Do levels of alcohol consumption differ between military veterans and non-veterans?* I find that on average, US adults who are military veterans consume more alcohol than non-veterans.
3. *Which states have the highest prevalence of smoking adults?* I find that the five states with the highest rates of smoking are West Virginia, Guam (a US territory), Kentucky, Tennessee, Ohio, and the five states with the lowest rates of smoking are Puerto Rico (a US territory), Utah, California, Hawaii, and Washington state.
