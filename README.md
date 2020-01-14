# EDA: Exploratory Data Analysis

A Python exploratory Data Analysis on the **Kenya Primary Schools** dataset, downloaded from  [africaopendata](http://www.africaopendata.org) to the file **kenya_primary_schools.csv** and included in this EDA folder.

## 1. Domain knowledge
The first thing we should do when we start working with a new dataset is obtaining some specific konwledge about the area of interest. This will help us to understand the following steps to achieve. 

For this dataset, we should study the Kenya’s national education system, specially related to Primary School. As a result, we will adquire some basic knowledge about the topic, and will understand better the information given.

## 2. Brief analysis
The dataset contains **31.230 rows** and **38 features**. We find **12 object features (text)** and **26 numeric features (float64)**.
There´s only one **missing value** (NaN) in each column, except in features *X*, *Y* and *FID*.
![MissingValuesPerColumn](/images/MissingValuesPerColumn.png)

We check if  missing value is located in the same row for all the features. In that case, we drop the row.
