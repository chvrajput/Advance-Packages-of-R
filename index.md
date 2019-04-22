#PACKAGE 1 : DataExplorer - To perform Exploratory Data Analytics

#install the package
install.packages("DataExplorer")
#load the package
library(DataExplorer)

data(iris)
#to check the missing value %
plot_missing(iris)

#To create the report of Exploratory Data Analytics
create_report(iris)
