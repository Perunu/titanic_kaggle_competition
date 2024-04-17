# Titanic - Survival Prediction

# Project Overview
This is the Titanic ML competition from [Kaggle](https://www.kaggle.com/competitions/titanic)  
According to Kaggle, ..."it's the best, first challenge for you to dive into ML competitions and familiarize yourself with how the Kaggle platform works."  

The competition is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

# Installation and Setup

## Codes and Resources Used

- **Editor Used:** Jupyter Lab
- **Python Version:** 3.11.7

## Python Packages Used

- **General Purpose:** warnings
- **Data Manipulation:** pandas, numpy
- **Data Visualization:** seaborn, matplotlib
- **Machine Learning:** scikit, sklearn

# Data

## Source Data
- [train.csv](https://www.kaggle.com/competitions/titanic/data)
    - from Kaggle's Titanic web page
- [test.csv](https://www.kaggle.com/competitions/titanic/data)
    - from Kaggle's Titanic web page

## Data Acquisition
Simply navigate to the datasets using either link above and download the files.

## Data Preprocessing
- [titanic_combined_dataset_cleaned_processed.csv](data/titanic_combined_dataset_cleaned_processed.csv)
    - I combined both train and test to clean and perform EDA
- [train.cleaned.csv](data/train.cleaned.csv)
    - modified train.csv file ready for modeling
- [test.cleaned.csv](data/test.cleaned.csv)
    - modified test.csv file ready for modeling

# Code structure

```
├── data
│   ├── train.csv
│   ├── test.csv
│   ├── titanic_cleaned_processed.csv (file after I prepared data for modeling)
├── README.md
├── titanic_exploration.ipynb
└── .gitignore 
```

# Results and evaluation
I was 12,910 with a 0.76076 Score<br>
This was my first ever solo exploration, I supposed it could have been worse :)

# Future work
I may revisit this in the future and try again after I have more experience with competitions.

# Acknowledgments/References
[Hackers Realm](https://www.youtube.com/@HackersRealm) YouTube channel did a video on this competition and I cross-referenced/checked my work against this video.

# License
[Subject to Competition Rules](https://www.kaggle.com/competitions/titanic/rules#7-competition-data)