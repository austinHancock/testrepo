# testrepo

This repository contains my data science profile

```{r, echo=FALSE}
skill <- c("Computer Programming","Math","Statistics","Machine Learning","Domain Expertise","Communication/Presentation", "Data Visualization")
score <- c(2,3,3,1,4,5,4)
profile <- data.frame(skill, score)
barplot(score, names.arg=skill, main="Austin", xlab="Skill", ylab="Score")
```
