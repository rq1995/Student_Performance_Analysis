
# Mini project-Analysis of student preference

Ruoqi xu   2018-01-28

## Goal
In this project, I am willing to find the best model to predict the student's final grade based on they preference in school. 

## Data

I use part of the [student preference](http://archive.ics.uci.edu/ml/datasets/Student+Performance) data from UCI ML repo.

#### Data Set Information:
This data approach student achievement in secondary education of two Portuguese schools. 

citation: P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7. 


## Analysis

#### Data wrangling
#### Data Vis (EDA)  
#### Basic feature selection
#### Model selection
#### Feature selection again
#### Split dataset and train again

- All analysis part included in [here](./src/Student_preference_analysis.ipynb)
- Users can use jupyter notebook to open it.

## Final Report
- Users can check the final report in [here](./doc/report.md)

## Project structure
    |- CITATION.md
    |
    |- README.md
    |
    |- LICENSE.md
    |
    |- doc/           # directory for documentation, one subdirectory for manuscript
    |
    |- data/          # data for storing fixed data sets
    |
    |- src/           # any source code
    |
    |- from_partner/           # any compiled binaries or scripts
    |
    |- results/       # output for tracking computational experiments performed on data

## Dependencies

- The analysis was performed with Python 3 and Jupyter notebook.

- Python package used

  ```
numpy
pandas
sklearn
Seaborn
collections
Other tools
pickle
matplotlib
```