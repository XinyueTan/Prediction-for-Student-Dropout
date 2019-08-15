# Prediction
## Goal of the analysis

In this project, I will be working towards buildimg different models (e.g.:  CART, C4.5 and C5 classification algorithms) to predict student course dropout and then comparing those models. 

## Packages Required
```
install.packages("tidyr")
install.packages("dplyr")
install.packages("psych")
install.packages("caret")
install.packages("C50")
```

## Procedures
1. Load drop_out.csv file as a data frame
2. Seperate the dataset into a training set and a test set by randomly selecting 25% of the students to be the test dataset and leaving the remaining 75% for the training set
3. Visualize the relationships between variable "Complete" and other variables
4. Construct a classification tree that predicts complete using the caret package
5. Predict results from the test data and describe import attributes of this test, and determine if the predictive model of student performance is successful
6. Repeat step 4 and 5 using C4.5 and C5.0 respectively
7. Compare all three models at once with caret

## Visualization
<img src="https://user-images.githubusercontent.com/46146748/63124124-8d5a5900-bf78-11e9-9f63-9c5da08d2dda.png" width="600">

## Background
Prediction of student behavior has been a prominant area of research in learning analytics and a major concern for higher education institutions and ed tech companies alike. It is the bedrock of [methodology within the world of cognitive tutors](https://solaresearch.org/hla-17/hla17-chapter5/) and these methods have been exported to other areas within the education technology landscape. 

The ability to predict what a student is likely to do in the future so that interventions can be tailored to them has seen major growth and investment, [though implementation is non-trivial and expensive](https://www.newamerica.org/education-policy/policy-papers/promise-and-peril-predictive-analytics-higher-education/). Although some institutions, such as [Purdue University](https://www.itap.purdue.edu/learning/tools/forecast.html), have seen success we are yet to see widespread adoption of these approaches as they tend to be highly institution specific and require very concrete outcomes to be useful. 

## Relevant Materials about Prediction
### Related Readings

[Adhatrao, K., Gaykar, A., Dhawan, A., Jha, R., & Honrao, V. (2013). Predicting Studentsâ Performance Using ID3 and C4. 5 Classification Algorithms. International Journal of Data Mining & Knowledge Management Process, 3(5).](https://arxiv.org/ftp/arxiv/papers/1310/1310.2071.pdf)

[Brooks, C. & Thompson, C. (2017). Predictive modelling in teaching and learning. In The Handbook of Learning Analytics. SOLAR: Vancouver, BC](https://solaresearch.org/hla-17/hla17-chapter5/)

[The caret package](https://topepo.github.io/caret/train-models-by-tag.html)

[The C50 package](https://topepo.github.io/C5.0/)

[Pradhan, C. (2016). What are the differences between ID3, C4.5 and CART? Quora](https://www.quora.com/What-are-the-differences-between-ID3-C4-5-and-CART)


### Related Videos

[Jalayer Academy. (2015). R - Classification Trees (part 1 using C5.0)](https://www.youtube.com/watch?v=5NquIfQxpxk)


## Author
[Katherine Tan](www.linkedin.com/in/katherine-tan-2019), M.S student in Learning Analytics at Teachers College, Columbia University
