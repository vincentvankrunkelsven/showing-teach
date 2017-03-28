---
title       : Testing subexercises
description : This thing is meant to test subexercises

--- type:TabExercise key:ed98f7522c
## TabExercise

This is a tabexercise. ASF
XP should be defined at subexercise level.

*** =pre_exercise_code
```{python}
connect('postgresql', 'dvdrental')
```

*** =sample_code
```{sql}
-- sql code comes here
```

*** =type1: NormalExercise
*** =key1: e7cd8d45cb0
*** =xp1:50
*** =instructions1
Do some stuff

*** =solution1
```{sql}
SELECT film_id, title FROM film;
```

*** =sct1
```{python}
Ex().check_result()
```

*** =type2: MultipleChoiceExercise
*** =key2: 216ce6d2106
*** =xp2:50
*** =question2
What do you think?

*** =possible_answers2
- One
- Two
- Three
- Four

*** =sct2
```{python}
msg1 = "Wrong 1"
msg2 = "Option 2 is correct, great!"
msg3 = "Wrong 2"
msg4 = "Wrong 3"
Ex().test_mc(2,[msg1,msg2,msg3,msg4])
```

*** =type3: NormalExercise

*** =key3: f643f41db4
*** =xp3:50
*** =instructions3: Do some stuff part 3.
*** =solution3
```{sql}
SELECT film_id, title FROM film
```

*** =sct3
```{python}
Ex().check_result()
```

*** =type4: NormalExercise
*** =key4: 2805953617
*** =xp4:50
*** =instructions4: Do some stuff part 4.
*** =solution4
```{sql}
SELECT film_id, title FROM film
```

*** =sct4
```{python}
Ex().check_result()
```

*** =type5: NormalExercise
*** =key5: b78ff98e7e
*** =xp5:50
*** =instructions5: Do some stuff part 4.
*** =solution5
```{sql}
SELECT film_id, title FROM film
```

*** =sct5
```{python}
Ex().check_result()
```


--- type:BulletExercise key:ac8d4e05c2
## BulletExercise

This is a bullet exercise.
XP should be defined at subexercise level.

*** =pre_exercise_code
```{python}
connect('postgresql', 'dvdrental')
```

*** =sample_code
```{python}
-- sql code comes here.
```

*** =type1: NormalExercise
*** =key1: f4b7465ve8467
*** =xp1: 50
*** =instructions1: Do some stuff
*** =solution1
```{sql}
SELECT film_id, title FROM film;
```

*** =sct1
```{python}
Ex().check_result()
```

*** =type2: NormalExercise
*** =key2: fd34f3517f35
*** =xp2: 50
*** =instructions2: Do some stuff part 2.
*** =solution2
```{sql}
SELECT film_id, title FROM film
```

*** =sct2
```{python}
Ex().check_result()
```


*** =type3: NormalExercise

*** =xp3: 50
*** =instructions3: Do some stuff part 3.
*** =solution3
```{sql}
SELECT film_id, title FROM film
```

*** =sct3
```{python}
Ex().check_result()
```