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
[1] 0+2i
[1] TRUE

# 2. Створити вектори, які: містить послідовність з 5 до 75; містить числа 3.14, 2.71, 0, 13; 100 значень TRUE.
```{r}
x <- 5:75
y <-c(3.14, 2.71, 0.13)
z <-c(rep(TRUE, 100))
print(x)
print(y)
print(z)
```
[1]  5  6  7  8  9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31
[28] 32 33 34 35 36 37 38 39 40 41 42 43 44 45 46 47 48 49 50 51 52 53 54 55 56 57 58
[55] 59 60 61 62 63 64 65 66 67 68 69 70 71 72 73 74 75
[1] 3.14 2.71 0.13
[1] TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE
 [17] TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE
 [33] TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE
 [49] TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE
 [65] TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE
 [81] TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE TRUE
 [97] TRUE TRUE TRUE TRUE
 
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
