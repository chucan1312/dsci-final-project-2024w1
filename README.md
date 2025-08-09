# 📊 Final Data Science Project

This repository contains the final project for a Data Science course, originally developed in a Jupyter Notebook environment using R. This project analyzes whether player experience can predict monthly playtime on a Minecraft research server used by UBC's PLAI lab to train embodied AI agents. The project involves a data-driven investigation, applying key techniques such as data wrangling, visualization, and modeling.


## 📁 Contents

- `Overview.ipynb`: A simplified overview of the dataset and the context of the project.
- `Group Project Final Report.ipynb`: A detailed, full-length version of our data science workflow including exploratory data analysis, predictive modeling, visualization and conclusions.


## 🧪 How to Run

1. Make sure R is installed (recommended: version 4.2 or higher).
2. Install the required R packages listed below.
3. Install the IRkernel for Jupyter:
   ```r
   install.packages("IRkernel")
   IRkernel::installspec()
4. Open the .ipynb files using Jupyter Notebook, JupyterLab, or VS Code with the R kernel.
5. Run all cells in either notebook to reproduce the results.

## 📦 Required Packages

To run this project locally, install the following R packages:

```r
install.packages(c(
    "tidyverse",
    "tidymodels",
    "infer",
    "broom",
    "readr",
    "dplyr",
    "ggplot2",
    "kableExtra",
    "kknn",
    "repr"
))


## ## 👥 Authors

This project was completed by a student group of 3 as part of the DSCI 100 course at the University of British Columbia.