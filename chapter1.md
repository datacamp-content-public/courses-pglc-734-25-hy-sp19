---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

Independent one-sample t-test

`@instructions`
Instructions

`@hint`
Hint

`@pre_exercise_code`
```{r}
# create a vector of Los Banos USD school API scores
API <- c(787,522,735,624,514,732,854,725,769,773,826,757,796)
# convert API scores to a dataframe named losbanosusd
losbanosusd <- data.frame(API)
```

`@sample_code`
```{r}
print(losbanosusd)
# install pastecs package if not yet installed, then load
if ("pastecs" %in% rownames(installed.packages()) == FALSE)
 {install.packages("pastecs", repos = "http://cran.r-project.org")}
require("pastecs")
round(stat.desc(losbanosusd),2)
```

`@solution`
```{r}
Solution
```

`@sct`
```{r}

```
