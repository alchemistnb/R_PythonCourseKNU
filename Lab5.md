# Function #1

```{r}
pmean ("specdata", "sulfate", 1:10)

pmean ("specdata", "sulfate", 55)

pmean ("specdata", "nitrate")
```
повертає помилку: returning NAargument is not numeric or logical: returning NA [1] NA NA NA NA NA NA NA NA NA NA

# Function #2

```{r}
complete("specdata", 1)
```
id nobs  
1 	117  

```{r}
complete("specdata", c(2, 4, 8, 10, 12))
```
id nobs    
2	1041  		
4	474  
8	192  		
10 148  
12	96  

```{r}
complete("specdata", 50:60)
```
id nobs  
50	459  
51	193  
52	812  
53	342  
54	219  
55	372  
56	642  
57	452  
58	391  
59	445  
60  448  

# Function #3


