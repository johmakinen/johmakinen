


# Data science portfolio by Johannes Mäkinen



[![Linkedin: johmakinen](https://img.shields.io/badge/-Johannes%20Mäkinen-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/johmakinen/)](https://www.linkedin.com/in/johmakinen/)



This portfolio is a compilation of projects and notebooks which I have created for data analysis or exploration of machine learning algorithms.

## Stand-alone projects.

### Portfolio Optimization [![github_link](https://img.shields.io/badge/-Github-blueviolet?style=flat-square&logo=github&logoColor=white&link=https://github.com/johmakinen/Portfolio-Optimization)](https://github.com/johmakinen/Portfolio-Optimization)



The purpose of this project was to create a simple interactive tool to optimize the asset allocation of a stock portfolio. I wanted to do an automatic data retrieval from Yahoo Finance and optimize the asset portfolio using my knowledge of portfolio optimization and investment science. [Markowitz model](https://en.wikipedia.org/wiki/Markowitz_model) was used for the implementation. Most of the difficulties came from learning frontend development (Flask, JS, HTML) from scratch. The UI of the tool is quite barebones as I was more interested in implementing the method rather than spending time on the UX.

### Course search tool for my university [![github_link](https://img.shields.io/badge/-Github-blueviolet?style=flat-square&logo=github&logoColor=white&link=https://github.com/johmakinen/University-course-search-tool)](https://github.com/johmakinen/University-course-search-tool)



At the time of creation, you could not search courses for only certain periods. You could only search for courses that overlap the period you were searching; e.g. the problem was: "I want to see courses only in period 1, not courses that are in period 1 AND 1-2". This annoyed me and made my life much harder when trying to plan my courses ahead of time. Thus, I created a better way to search for courses at my university. The tool doesn't work for *you* as the university didn't allow me to publish the course data, but you can see the pipelines that I've created.

### Multiple Correspondence Analysis on sleeping pads (MCA) [![github_link](https://img.shields.io/badge/-Github-blueviolet?style=flat-square&logo=github&logoColor=white&link=https://github.com/johmakinen/MCA-on-sleeping-pads/blob/main/MCA_report.pdf)](https://github.com/johmakinen/MCA-on-sleeping-pads/blob/main/MCA_report.pdf)

I was in search of a new sleeping pad for my hiking trips. As a quite perfectionist, I usually want to analyse all the things that I'm about to buy, so that I'm not let down, waste money on subpar equipment or otherwise feel bad about my purchase later. Therefore, I analysed some common sleeping pads and figured out what kind of a pad would be a good buy. To do this, I preprocessed the data and applied [MCA](https://en.wikipedia.org/wiki/Multiple_correspondence_analysis) to get insights into the underlying structure of the data.

### Optimal flight with a glider [![github_link](https://img.shields.io/badge/-Github-blueviolet?style=flat-square&logo=github&logoColor=white&link=https://github.com/johmakinen/Optimal-flight-with-a-glider/blob/main/Glider_project_pdf_full.pdf)](https://github.com/johmakinen/Optimal-flight-with-a-glider/blob/main/Glider_project_pdf_full.pdf)

This was a quite large school-related project, where we optimized the flight path (control policy) of a hang glider in different situations. The objective was to maximize the length of the glide in the direction of the x-axis. The project utilized dynamic optimization (control theory) and simulation using Matlab. [Direct collocation](https://en.wikipedia.org/wiki/Trajectory_optimization#Direct_collocation) and [Sequential quadratic programming](https://en.wikipedia.org/wiki/Sequential_quadratic_programming) were used to make the method more efficient.


## Separate notebooks for smaller projects.

### Regression

### Classification

#### Predict churning customers [![github_link](https://img.shields.io/badge/-Github-blueviolet?style=flat-square&logo=github&logoColor=white&link=https://github.com/johmakinen/Various_projects/blob/main/Notebooks/Credit_card_churn.ipynb)](https://github.com/johmakinen/Various_projects/blob/main/Notebooks/Credit_card_churn.ipynb)

In this analysis, I explored a [dataset](https://www.kaggle.com/sakshigoyal7/credit-card-customers) of credit card customers and then created a Gradient Boosting Classifier to predict whether a customer would be churning out. This is an important task for many businesses because you can directly improve profits if you can improve customer retention. Using my model, we could target the customers that are predicted to churn out, and give them more benefits or target them with lucrative campaigns so that they would not drop out. The implemented model has high accuracy (both Precision & Recall > 90%), but is also simple enough to be understood easily. Upsampling was used to tackle the problem of highly imbalanced data.


### Clustering

### Natural language processing

### Neural networks

### Miscellaneous

#### House price data scraper [![github_link](https://img.shields.io/badge/-Github-blueviolet?style=flat-square&logo=github&logoColor=white&link=https://github.com/johmakinen/Various_projects/blob/main/Notebooks/house_scraper.ipynb)](https://github.com/johmakinen/Various_projects/blob/main/Notebooks/house_scraper.ipynb)

[Work in progress]

The objective is to create a data scraper for Finnish house data. The data is collected from one of the largest nationwide internet service for housing and real estate.
