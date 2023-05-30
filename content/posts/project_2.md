---
title: "Project 2: Linear Regression Model for Chris Paul Player Statistics"
date: 2022-06-28T19:56:11-06:00
draft: false
cover:
    image: img/ChrisPaulStats.png
    caption: 
    alt:

---

* The project aimed to build a model to help Chris Paul, a professional basketball player, identify the statistics that most influence his offensive ability, particularly points scored per game.
* Over 1,000 rows of game statistics were scraped from Chris Paul's page on Basketball Reference to build a linear regression model.
* The model was designed to provide interpretable and actionable insights that Chris Paul could incorporate into his playing strategy.
* The data collection involved scraping per game statistics for Paul’s entire career, totaling 1155 regular season games.
* A pairplot graph was built to visualize the data and identify any significant collinearities, after which redundant features were removed.
* Three different regression models were built: Linear Regression, Polynomial Regression, and Lasso Regression. The Linear Regression model was chosen for its simplicity and interpretability.
* The data consisted of Paul’s in-game stats (points, assists, steals, etc.) along with some categorical data such as home vs away, opponent, and date.
* The Linear Regression model revealed that steals and defensive rebounds were not significant predictors of points per game as their p-values were greater than 0.6.
* Field goal attempts and free-throw attempts were found to be the biggest indicators of points scored, with coefficients of 1.11 and 0.8 respectively, followed by three-point attempts with a coefficient of 0.39.
* Interestingly, offensive rebounds were found to be the largest deterrent of points scored, with a coefficient of -0.914.

[Linked to GitHub Repo](https://github.com/apeterson321/Chris-Paul-Statistics-Project)