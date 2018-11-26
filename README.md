# Assignment_2.5
States = rownames(US Arrests)
Get states names with ‘w’.

Get states names with ‘W’.

ans:

Get states names with ‘w’. ->

library(datasets)

x<-USArrests[order(USArrests$Murder),]

x<-rownames(x[46:50, ])

tolower(x)

Get states names with ‘W’. ->

library(datasets)

x<-USArrests[order(USArrests$Murder),]

x<-rownames(x[46:50, ])

toupper(x)

Prepare a Histogram of the number of characters in each US state.
ans:

hist(nchar(states), main = "Histogram",

xlab = "number of characters in US State names")
