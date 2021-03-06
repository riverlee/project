---
title: "Assets"
author: "Jiang Li"
date: "4/24/2018"
output: 
  html_document:
    toc: true
    keep_md: yes
    toc_float:
      collapsed: false
      smooth_scroll: false
---



## Inputs

**Data**

- Downloaded from https://www.kaggle.com/datasets

### Input file
[GDM/data/diabetes.csv](GDM/data/diabetes.csv)

### **As munged for usage in project:**
[GDM/munge/01-A.R](GDM/munge/01-A.R])

It loads the input file (**[GDM/data/diabetes.csv](GDM/data/diabetes.csv)**) and split the dataset into training (70%) and testing (30%) with R variable names:
- trainDat
- testDat

## Outputs

### Formal Problem statement (FPS)

- [GDM/FPS/FPS_for_predicting_diabetes.md](GDM/FPS/FPS_for_predicting_diabetes.md)

### EDA and Naive model performance

- [GDM/reports/project-performance.md](GDM/reports/project-performance.md)

###  Linear model performance
- [GDM/reports/model-performance-linear.md](GDM/reports/model-performance-linear.md)

### Tree model performance
- [GDM/reports/model-performance-rpart.md](GDM/reports/model-performance-rpart.md)

### Multiple models performance

We implemented several models which are glmnet,rpart,nnet,rf,svmRadial,xgbTree
- [GDM/reports/multiple-model.md](GDM/reports/multiple-model.md)
- **Model result in R object**: 
    - [GDM/result/models-list.RData](GDM/result/models-list.RData)
    
### Final model
- Final model is based on **xgbtree** [GDM/reports/Final-model.md](GDM/reports/Final-model.md)

    
### Model packages
- [GDM/pkgs/GDM.Models](GDM/pkgs/GDM.Models)
- A script to build the package is avaiable at [GDM/src/build-GDM-model-pkgs.R](GDM/src/build-GDM-model-pkgs.R)

### Score packages
- [GDM/pkgs/GDM.Score](GDM/pkgs/GDM.Score)
- A script to build the package is avaiable at [GDM/src/build-GDM-score-pkgs.R](GDM/src/build-GDM-score-pkgs.R)


### Development

Developed through Shiny App

- [GDM/app](GDM/app)
- Also avaiable at [https://riverlee2008.shinyapps.io/GDM_Shiny/](https://riverlee2008.shinyapps.io/GDM_Shiny/)
   



