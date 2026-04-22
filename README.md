# Course project: Primary analysis of data sets of various types

**University:** South Ural State University (SUSU), VirtUm Center  
**Direction:** 01.03.02 "Applied Mathematics and Computer Science"   
**Student:** Stepanenko Alexandra Maksimovna   
**Group:** ET-113  
**Year:** 2026   

## Project description

This repository contains the source code and supporting materials for a course project on the search and initial analysis of datasets of five main types:
- Tabular data
- Time series
- Images
- Text data
- Audio data

The purpose of the work is to gain practical skills in assessing the quality of data, visualizing it, and preparing it for use in machine learning and artificial intelligence tasks.


## Repository structure

-   `data/`: Source datasets
-   `notebooks/`: Jupyter notebooks with analysis for each data type.
-   `src/`: Python source code.
-   `report/`: Course project report files.
-   `predict.py`: Script for predicting on new data.
-   `requirements.txt`: List of dependencies.

## Used datasets

| Data type | Name | Source | Description |
|------------|----------|----------|------------------|
| **Tabular** | CWRU Bearing Dataset | [Kaggle](https://www.kaggle.com/datasets/brjapon/cwru-bearing-datasets) | Multiclass classification of bearing condition based on statistical vibration features. |

## Analysis steps

### 1. Tabular data

- Visualization of feature distribution.
- Visualization of features.
- Analysis for missing values.
- Correlation analysis.
- Elimination of duplicates.
- Analysis and processing of outliers.
- Data filtering.
- Adding noise.

## Installation and launch

### 1. Cloning the repository
```bash
git clone git@github.com:Lexxxi42/susu-eda-coursework.git
cd susu-eda-coursework
```

## Creating a virtual environment 

```bash
python -m venv venv
source venv/bin/activate
```

## Installing dependencies
```bash
pip install -r requirements.txt
```
