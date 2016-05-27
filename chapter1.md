---
title       : Orientation
description : Chapter on orientation

--- type:RStudioMultipleChoiceExercise xp:50 skills:1 key:9f04a059fc
## Using the tab button

If you want to be a real data science master, the 'tab' button on your keyboard will quickly become your best friend. You can use the tab button in various settings to automatically provide a list of all available functions, arguments, packages, objects, etc. 

In the last video, you saw Garrett use `read.csv()`, which is a function used to import CSV files into R. `read.csv()` takes many arguments. Enter `read.csv()` and then hit the tab button (making sure the cursor is in between the parentheses). 

Which of the following is not an argument to the `read.csv()` function?

*** =instructions
- `file`
- `fill`
- `xlab`
- `header`

*** =hint
Hit the 'tab' button while the cursor is in between the parentheses. From there, you can scroll through the options with the 'up arrow' and 'down arrow' keys to check if each of the options is there. 

*** =pre_exercise_code
```{r,eval=FALSE}
# no pec
```

*** =sct
```{r,eval=FALSE}
msg1 <- "Try again! `file` is a required argument to the `read.csv()` function."
msg2 <- "Try again! `fill` is an argument to the `read.csv()` function." 
msg3 <- "Correct! The `xlab` argument is often seen in plotting functions to set the x-axis label, but not when importing data." 
msg2 <- "Try again! `header` is an argument to the `read.csv()` function."

test_mc(3, feedback_msgs = c(msg1, msg2, msg3, msg4))
```

