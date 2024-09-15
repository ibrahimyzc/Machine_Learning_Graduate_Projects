# Machine Learning Graduate Projects

This repository contains homework projects completed as part of the **Machine Learning graduate class** at the **University of Pittsburgh** during my PhD in Applied Mathematics. Each week, different machine learning topics and techniques were explored through hands-on assignments.

## Overview

The assignments focus on various key aspects of machine learning, covering concepts such as Exploratory Data Analysis (EDA), regression models, classification metrics, and optimization techniques. Below is a summary of the first twelve assignments:

### Assignment 1: Exploratory Data Analysis (EDA) with `ggplot2` and `lm()`
In this assignment, we introduced the **grammar of graphics** in R with `ggplot2`, focusing on **Exploratory Data Analysis** (EDA). The primary goal was to visualize and interpret datasets using basic programming syntax, providing insights into model results using the formula interface in `lm()` for linear modeling.

### Assignment 2: Fitting Polynomial Regression Models
We worked on fitting and comparing **polynomial regression models** ranging from degree 1 (linear) to degree 9. This assignment explored the impact of **sample size** and **noise** on model selection by fitting models with synthetic datasets. Techniques such as **cross-validation** and **model performance evaluation** were emphasized.

### Assignment 3: Binary Classification Metrics and Model Comparison
In this project, we calculated various **binary classification metrics** such as **accuracy, ROC curve, AUC**, and **confusion matrix**. We used the `caret` and `yardstick` packages for performance assessment of binary classifiers and compared models using **calibration curves**.

### Assignment 4: Likelihoods, Priors, and Posteriors with Binomial Data
This assignment focused on the **mathematics of likelihoods, priors, and posteriors**. We worked with **binomially distributed data** and performed calculations in R using **loops, functions**, and **ggplot2** for visualizations. Derivations and expressions were presented using **LaTeX**.

### Assignment 5: Gaussian Distributions and Optimization
We explored **Gaussian distributions**, focusing on **derivatives, change-of-variable transformations**, and using the `optim()` function for **numerical optimization**. In this assignment, we practiced solving **optimization problems** while performing derivations.

### Assignment 6: Estimating Mean and Noise with Laplace Approximation
In this assignment, we worked on estimating an **unknown mean (μ)** and **unknown noise (σ)** for a Gaussian likelihood. We visualized the log-posterior and used **Laplace Approximation** to approximate the joint posterior distribution on μ and σ, including both programming and derivations.

### Assignment 7: Fitting and Assessing Linear Models
This homework involved **fitting linear models** using formulas and analyzing their performance. We fitted and predicted using **linear basis function models**, ranging from simple to complex. The goal was to select the best model using **train/test split** and the **log-Evidence** (log marginal likelihood).

### Assignment 8: Bayesian and Non-Bayesian Linear Models with Regularization
In this assignment, we reviewed fitting **Bayesian and non-Bayesian linear models** with varying levels of complexity. We compared predictive performance and uncertainty, and introduced regularization with **Lasso regression**. Additionally, we learned how priors can regularize coefficients in Bayesian models.

### Assignment 9: Non-Bayesian Regularization (Ridge, Lasso, Elastic Net)
This homework focused on **non-Bayesian regularization** techniques, specifically **Ridge, Lasso**, and **Elastic Net** models. We tuned the regularization strength (λ) to select the best model using the **glmnet** and **caret** packages, while exploring how regularization affects coefficients.

### Assignment 10: Binary Classification with Logistic Regression and Advanced Methods
In this assignment, we worked on **binary classification**. We fitted **non-Bayesian and Bayesian logistic regression models**, using **Laplace Approximation** for Bayesian models. Additionally, we tuned advanced methods such as **neural networks** and **random forests** using **cross-validation**, and visualized the predictive trends.

### Assignment 11: Binary Classification with XGBoost and Neural Networks
In this assignment, we explored the issue of **linear separability** and its effect on **logistic regression**. We trained both unregularized and regularized logistic regression models, as well as **neural networks**, **random forests**, and **gradient boosted trees** with **XGBoost** to compare performance.

### Assignment 12: Learning Distributions from Data
This assignment tested our understanding of the concepts, mathematics, and programming involved in learning distributions from data. We performed a combination of **derivations** and **programming** to solve problems and assess different distributions from given datasets.

## Technologies Used

- **R**: The main programming language used for all assignments. We utilized R for data preprocessing, statistical analysis, and model development. R's robust set of libraries and packages for machine learning, data visualization, and statistical computing were essential for this course.
  
- **ggplot2**: Used extensively for creating visualizations in assignments involving Exploratory Data Analysis (EDA). **ggplot2** allowed us to create complex, multi-layered graphics to understand data distributions, model predictions, and other analysis results.

- **caret**: The **caret** package was fundamental for handling machine learning workflows. We used it for model training, evaluation, cross-validation, and hyperparameter tuning across various classification and regression tasks.

- **yardstick**: This package helped us evaluate model performance with metrics such as accuracy, ROC curves, confusion matrices, and AUC, especially in binary classification tasks.

- **glmnet**: A key package for performing **Ridge**, **Lasso**, and **Elastic Net** regression. It enabled us to efficiently fit regularized linear models and tune the regularization strength for improved model generalization.

- **LaTeX**: We used **LaTeX** within RMarkdown documents for typesetting complex mathematical equations and derivations, especially when presenting theoretical concepts like likelihoods, priors, and posteriors.

- **optim()**: The `optim()` function in R was crucial for solving **optimization problems**, particularly in assignments focused on Gaussian distributions and optimization techniques.

- **randomForest**: We employed the **randomForest** package to build ensemble models for classification tasks, which provided robust performance in the presence of non-linear decision boundaries and high-dimensional data.

- **nnet**: For training **neural networks**, we used the **nnet** package, which enabled us to explore basic neural network architectures and apply them to classification problems.

- **xgboost**: We used **XGBoost** for training **gradient boosted trees**, which provided competitive performance in classification tasks, particularly in handling large datasets with complex patterns.

- **tidyverse**: The **tidyverse** collection of R packages (including dplyr, tidyr, and others) was essential for data manipulation and wrangling. These tools allowed us to efficiently clean, reshape, and analyze datasets before applying machine learning models.
