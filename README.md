# JHU_PML_Project
This repo stores the rmarkdown and html report created for the Practical Machine Learning course of JHU Data Scientist Track.

The unauthorized usage is prohibited. 

# Execuitive Summary
Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. 

In this project, I will use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

The core business problem is to help clients who are using the equipment to tell which class their posture is belonging to. This is a typical question of classification. The expected output will be a predictive model that provide this information, focusing on providing highest precision. \

The Data will be cleansed by treating missing data, wrong data type and overfitting because of over power. The major techniques used here are standardization and feature reduction by drop variables.Three models has been tested, a support vector machine, a random forest and a neauralnet multinomial work model. By the comparison in accuracy, kappas and performances for each individual class, the **support vector machine model(SVM-Poly)** proved to have the best performances. Hence, this model has been chosen to predict. 

This report builds an algorithm, which is capable of detecting the posture of users effectively. The business problem has been directly solved. 
