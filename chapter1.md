---
title       : Insert the chapter title here
description : Insert the chapter description here
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:c60aa91c13
## A really bad movie

Have a look at the plot that showed up in the viewer to the right. Which type of movie has the worst rating assigned to it?

*** =instructions
- Adventure
- Action
- Animation
- Comedy
- Horror

*** =hint
Have a look at the plot. Which color does the point with the lowest rating have?

*** =pre_exercise_code
```{r}
# The pre exercise code runs code to initialize the user's workspace.
# You can use it to load packages, initialize datasets and draw a plot in the viewer

books <- read.csv("http://s3.amazonaws.com/assets.datacamp.com/course/introduction_to_r/books.csv")

library(ggplot2)

ggplot(books, aes(x = runtime, y = rating, col = genre)) + geom_point()
```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad <- "That is not correct!"
msg_success <- "Exactly! There seems to be a very bad action movie in the dataset."
test_mc(correct = 2, feedback_msgs = c(msg_bad, msg_success, msg_bad, msg_bad))
```

--- type:NormalExercise lang:r xp:100 skills:1 key:a720588156
## More movies 

In the previous exercise, you saw a dataset about books. In this exercise, we'll have a look at yet another dataset about books!

A dataset with a selection of books, `movie_selection`, is available in the workspace.

*** =instructions
- Check out the structure of `movie_selection`.
- Select books with a rating of 5 or higher. Assign the result to `good_books`.
- Use `plot()` to  plot `good_books$Run` on the x-axis, `good_books$Rating` on the y-axis and set `col` to `good_books$Genre`.

*** =hint
- Use `str()` for the first instruction.
- For the second instruction, you should use `...[movie_selection$Rating >= 5, ]`.
- For the plot, use `plot(x = ..., y = ..., col = ...)`.
- Hint

*** =pre_exercise_code
```{r}
# something new
test <- read.csv("http://s3.amazonaws.com/assets.datacamp.com/production/course_3405/datasets/test.csv")
```

*** =sample_code
```{r}
test
```

*** =solution
```{r}

```

*** =sct
```{r}

```

--- type:VideoExercise lang:r xp:50 skills:1 key:20047b0836
## Welcome to the course

*** =slidesKey
80c74ba03f98aa57ae3ef1a406aafd64

--- type:NormalExercise lang:r xp:100 skills:1 key:21dd1a6850
## Test


*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}

```

*** =solution
```{r}

```

*** =sct
```{r}

```

--- type:VideoExercise lang:r xp:50 skills:1 key:25b4a8c306
## Some video

*** =slidesKey
b29a586c97c6f4b59533eefe5c15f50f
