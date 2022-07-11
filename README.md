# Titanic Disaster

Analysis of the Titanic Disaster

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jofaval/titanic-disaster/blob/master/notebook.ipynb)&nbsp;[![Open in Kaggle](https://www.kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/jofaval/titanic-disaster-machine-learning-predictions)

## Table of contents

1. [📁 Data](#-data)
1. [📓 Description](#-description)
1. [✔️ Objective](#-objective)
1. [🧱 Tech stack](#-tech-stack)
1. [💹 Algorithms](#-algorithms)
1. [📊 Visualization](#-visualization)
1. [🤓 Conclusions](#-conclusions)
1. [©️ Credits](#-credits)

## 📁 Data
[↑ Back to the table](#table-of-contents)

The data is available at the official archive link:\
[https://www.kaggle.com/c/titanic](https://www.kaggle.com/c/titanic)

## 📓 Description
[↑ Back to the table](#table-of-contents)

This is the legendary Titanic ML competition – the best, first challenge for you to dive into ML competitions and familiarize yourself with how the Kaggle platform works.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

## ✔️ Objective
[↑ Back to the table](#table-of-contents)

To succcessfully predict the survivance of the passengers and what goes into their survival. It's a starter project, so the given objective is as simple as to tackle the challenge and complete a machine learning project.

## 🧱 Tech stack
[↑ Back to the table](#table-of-contents)

Python, that's it! R is a programming language that, as for the moment being, I have no experience with, even though it's powerful and broadly used, but I'd dare to say that no more than Python.

And one of the strongest points, if not the most, about Python, are it's libraries, so... the libraries I've used are:

- Pandas, data manipulation with an ease of use and exploration data analysis.
- Numpy, a really strong linear algebra library, used in the project for it's statistics utilities, SciPy may be an alternative, but I have no experience at all with it.
- Matplotlib and Seaborn, both fantastic libraries for data visualization, and they complement each other.
- Scikit-Learn, the library used for Machine Learning and statistics models: Linear Regression, SVR, Lasso, Ridge, etc.
- Tensorflow and Keras, the industry standard for Deep Learning, the way to go, not really, it's just that for now I don't have that many experience with PyTorch

## 💹 Algorithms
[↑ Back to the table](#table-of-contents)

I used three algorithms, Logistic Regression, XGBoost and Random Forest.

They're all really powerful, but Random Forest had the higher scores all and all while being consistent. But they were all quite close. Obviously balancing a dataset kind of evens the scores, but not that much, so it was quite a nice surprise to see the logistic regression performing well, in comparison with such titanic techniques (pun intended).

## 📊 Visualization
[↑ Back to the table](#table-of-contents)

In this case, there were some kind of cool visualizations, apart from the obvious distribution and correlation plots, I added some pie charts to detect imbalancement, and discovered a neat trick for visualize the boxplots that's much cleaner than what I used to do.

I've also used a technique for the missing values visualization that I found while researching about EDA (Exploratory Data Analysis). Which is to use a heatmap so that the missing values get selected, and helps us visualize where the missing values are, and if we could even split the dataset to remove the data. I feel it's easier to understand than just the classic numbers. But it's also slower to plot, and can't easily be applied to larger datasets, nor it may be worth it.

## 🤓 Conclusions
[↑ Back to the table](#table-of-contents)

Whenever possible, even on a perfect, ready-to-work dataset, read the abstract, the papaer, whatever information it is that you may have at hand, it truly helps understand the evaluation of the results and it's tuning.

And, once again, distribution can do wonders, having a distributed dataset is truly important, and if you don't have one, you can create it, undersampling is the best option around, unless you can actually create/collect reliable synthethic data, which is not the case.

## ©️ Credits
[↑ Back to the table](#table-of-contents)

The data was uploaded and given by Kaggle, a company owned by Google, so they're the ones to credit the dataset to, but I do not seem to find the team that actually collected that information.