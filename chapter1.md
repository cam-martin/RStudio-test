---
title       : Introduction to data
description : StatsWithR Lab2

--- type:RStudioMultipleChoiceExercise xp:50 skills:1 key:9f04a059fc
## Filtering and Counting

Create a new data frame that includes flights headed to SFO in February, and save 
this data frame as `sfo_feb_flights`. How many flights meet these criteria? 

*** =instructions
- <li> 68 </li>
- <li> 1345 </li>
- <li> 2286 </li>
- <li> 3563 </li>\
- <li> 32735 </li>

*** =hint
Remember the `|` operator allows you to filter for more than one variable. 

*** =pre_exercise_code
```{r,eval=FALSE}
library(dplyr)
library(ggplot2)

```

*** =sct
```{r,eval=FALSE}
msg1 <- "Try again! Look at the data frames dimensions with the `dim()` fucntion."
msg2 <- "Try again! The data frames dimensions can be displayed with the `dim()` fucntion." 
msg3 <- "Correct! There are 3,563 flights heading to San Francisco." 
msg2 <- "Try again! Use `dim()` fucntion to display the data frames dimensions."

test_mc(3, feedback_msgs = c(msg1, msg2, msg3, msg4))
```

