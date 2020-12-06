# Analyze-A-B-Test-Results
This project was completed as part of the course requirements of Udacity's [Data Analyst Nanodegree certification.](https://www.udacity.com/course/data-analyst-nanodegree--nd002)

### Overview: ###
The project is about ***A/B testing*** where the goal is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

### Statistical Analysis: ###
* Bootstrapping sampling distributions and p-value calculations
* Z-core tests
* Logistic regression

### Technologies Used: ###
* Python, Numpy, Pandas, Matplotlib, StatsModels, Scipy
* Jupyter Notebook

### Key Findings: ###
None of the variables have significant p-values. Therefore, we failed to reject the null and conclude that there is not sufficient evidence to suggest that there is an interaction between country and page received that will predict whether a user converts or not. In the bigger picture, based on the available information, we do not have sufficient evidence to suggest that the new page results in more conversions than the old page.Since the sample size is large continuing the testing of the new_page is likely not necessary. It is best to focus on the development of another new landing page.
