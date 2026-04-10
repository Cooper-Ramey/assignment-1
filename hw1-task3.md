# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

Type: Regression
Interest: Inference
n = 200
p = 4

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.

Type: Classification
Interest: Prediction
n = 30
p = 11

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

Type: Regression
Interest: Prediction
n = 52
p = 4

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

The advantages of working with a very flexible regression approach are that it is capable of capturing more details of the relationship. However, flexible models are also more likely to be overfitted and be inaccurate when it comes to data it hasn't seen before. A more flexible model is useful when you have a complicated relationship and a large amount of data. A more rigid model might be preffered if the relationship is less complex and/or you have less data to fit with. 

---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

A parametric approach relies on the assumption that there is a functional form F^ that the model uses to make predictions. A non-parametric approach allows the model to grow in complexity as it recieves more data. Parametric models are quite useful because they can use a relatively small amount of data to detect patterns. However, if the functional form is wrong then the model is inherently biased. Non-parametric models require far more data but can capture more complex relationships. 