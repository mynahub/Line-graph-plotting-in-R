# Line-graph-plotting-in-R
Tajima D values
library(dplyr)
library(ggplot2)

df <- read.csv("C:\\Users\\USER\\Documents\\Rh5_tajim.csv")
head(df)
ggplot(df, aes(x = R, y = D)) +
geom_line(color = "#f32E0D", size = 1.5) + theme_classic()
