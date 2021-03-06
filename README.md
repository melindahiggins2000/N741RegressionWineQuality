# N741RegressionWineQuality

N741 Homework 3 - Linear Regression Exercise with Wine Quality Data

Data provided can be retrieved from UCI Repository at [http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/](http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/) with details provided on the "Wine Quality Data Set" at [http://archive.ics.uci.edu/ml/datasets/Wine+Quality](http://archive.ics.uci.edu/ml/datasets/Wine+Quality).

Note: The original data files provided at the UCI Repository "winequality-red.csv" and "winequality-white.csv" while having the CSV filename extension are **NOT** comma delimited files. The delimiter is actually a semicolon `;` instead of a comma `,` and the variable names have spaces in them. To read these files you'll need to use `read.table()`. The R code below provides an example for reading in the Red Wine dataset.

```r
redWine <- read.table("winequality-red.csv",
                      header=TRUE,
                      sep=";")
```

You may also want to read the author's publication (which can be retrieved from [http://www.sciencedirect.com/science/article/pii/S0167923609001377](http://www.sciencedirect.com/science/article/pii/S0167923609001377)) to see how they did their analyses and what their results look like:

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. 
In Decision Support Systems, Elsevier, 47(4):547-553, 2009. 

## Homework 3 - details and Github repo

Homework 3 is detailed at Dr. Vicki Hertzberg's Github repository at [https://github.com/vhertzb/Regression-1](https://github.com/vhertzb/Regression-1). At her Github repository, she provides a slightly updated copy of the White Wine dataset with the variable names updated with the "spaces" removed from the variable names. A copy of "White_wines.csv" is also provided here for easy reference as well. This file is indeed a CSV comma delimited file and the variable names have the period `.` inserted for the spaces so the variable names import correctly. So, for this file `read.csv()` will work.

## Short Example with Red Wine Data

Be sure to check out the "redWine.Rmd" and associated output formats (HTML, DOCX and PDF) and Github markdown (MD) format included in this repository, see [https://github.com/melindahiggins2000/N741RegressionWineQuality/blob/master/redWine.md](https://github.com/melindahiggins2000/N741RegressionWineQuality/blob/master/redWine.md). 
