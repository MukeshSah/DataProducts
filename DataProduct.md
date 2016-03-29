DataProduct
========================================================
author: Mukesh Sah
date: March 26 2016

========================================================
## Disease Prediction Using R

1. How I have created dataset ?
2. Cleaning and Rensing dataset ?
3. Data Mining
4. ML Models
5. Results

========================================================

## Dataset

  The data set was manually created.
  Intervied 50 different people.
  
  ```r
    head(d1)
  ```
  
  ```
                                      symptoms  disease
  1 YELLOW DISCOLORATION OF WHITE PART OF EYES JAUNDICE
  2 YELLOW DISCOLORATION OF WHITE PART OF SKIN JAUNDICE
  3                               FEELING WEAK JAUNDICE
  4                                  LOW FEVER JAUNDICE
  5                            YELLOW PIGMENTS JAUNDICE
  6                            YELLOWISH COLOR JAUNDICE
  ```

========================================================

## Data Cleaning
  
  Empty values were removed.
  
  Disease columns was casted as factor.

```r
    colnames(d1)
```

```
[1] "symptoms" "disease" 
```

========================================================
## Ml Algorithms

  Using tm library stop word was removed.
  
  Frequency table was built based on the occurance of words.
  
  Also TF-ITF was calculated.





```
Error in library(tm) : there is no package called 'tm'
```
