# Missing Data Analysis: Multiple Imputation (MI) 

## This is an example of multiple imputation in missing data analysis

We will use the 'antisocial.csv' dataset. This dataset contains the following variables in the following order in the dataset: **anti1 anti2 anti3 anti4 read1 read2 read3 read4 male momage kidage homecog homeemo canti1 chomecog chomemo antigen**

The missing data are coded as -9 in the data. We are interested in performing a multiple regression analysis using final reading scores (READ4) as the outcome variable, and a set of four predictors: 

* initial antisocial behavior scores (ANTI1), 
* the amount of cognitive stimulation in the home (HOMECOG), 
* the amount of emotional support in the home (HOMEEMO), 
* and gender (MALE; female = 0, male = 1). 

Note that there are about 33% data missing on READ4. Data is complete on all of the predictors. 
