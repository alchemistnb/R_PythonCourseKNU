# 1. Створити змінні базових (atomic) типів. Базові типи: character, numeric, integer, complex, logical.
```{r}
v1 <- "NB"
v2 <- 22.09
v3 <- 1997
v4 <- 2i
v5 <- TRUE
```
[1] "NB"
[1] 22.09
[1] 1997
[1] 1997
[1] TRUE


x <- 5:75
y <-c(3.14, 2.71, 0.13)
z <-c(rep(TRUE, 100))
m1 <- c(0.5, 3.9, 0, 2)
m2 <- c(1.3, 131, 2.2, 7)
m3 <- c(3.5, 2.8, 4.6, 5.1)
cbind(m1, m2, m3)
l <-list("q", 22.5, 1, "FALSE", 1+2*x)
f <- factor(c("baby", "child", "adult"))
t <- c(1,2,3,4, NA, 6, 7, NA, 9, NA, 11)
match(NA, t)
sum(is.na(t))
dfr <- data.frame (10:20, 200:210)
dfr
names(dfr) <- c("1st", "2nd")
dfr
