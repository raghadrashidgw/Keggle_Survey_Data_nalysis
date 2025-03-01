[](https://i.pinimg.com/736x/a3/8e/ea/a38eea1aa87eae6fe4ce53188a1602b3.jpg)

# Insights from the Kaggle Survey: Trends in Machine Learning Framework Usage

![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/pragyy/datascience-readme-template?include_prereleases)
![GitHub last commit](https://img.shields.io/github/last-commit/pragyy/datascience-readme-template)
![GitHub pull requests](https://img.shields.io/github/issues-pr/pragyy/datascience-readme-template)
![GitHub](https://img.shields.io/github/license/pragyy/datascience-readme-template)
![contributors](https://img.shields.io/github/contributors/pragyy/datascience-readme-template) 
![codesize](https://img.shields.io/github/languages/code-size/pragyy/datascience-readme-template) 

> A guide to writing an amazing readme for your data science project.

The project title should be concise and self-explanatory so that the user can easily remember your project.

Add a cover banner to the top of your Readme to catch the attention of your readers.
I usually include images that are relevant to my project, and you can easily find any image for free online without worrying about copyright issues. However, if the work is not free, make sure to credit the proper owners in the references/acknowledgement section.

The colorful tiles beneath the title are known as badges, and they improve readability by providing quick insights into the github repository. I use [Shields IO](https://shields.io/). Depending on the project you can use the ones that are relevant. 

# Project Overview
This project analyzes data from the Kaggle Machine Learning and Data Science Survey to uncover trends in machine learning framework and programming language usage. The goal is to identify which frameworks and languages are most popular among different experience levels and how their adoption varies. 
The objectives:
1. Aggregating and visualizing both framework and programming language usage by job titles and experience level.
2. Identifying trends in framework and language preferences among beginners, intermediate users, and experts.
3. Generating insights to help data scientists, researchers, and organizations understand the evolving landscape of ML tools and programming languages.
4. The findings will be presented using data visualizations such as heatmaps, bar charts, and trend graphs for clearer interpretation.


# Data

## Source Data
https://www.kaggle.com/c/kaggle-survey-2021/data


## Data Preprocessing
The dataset consists of responses from the 2021 Kaggle Machine Learning & Data Science Survey, where each question is spread across multiple columns. For example, the question "What programming languages do you use on a regular basis?" is divided into up to eight columns, with each column representing a specific language. If a respondent selected Python, it appears in one column while the others remain empty, and the same applies to SQL, R, Java, and other languages.




# Results and evaluation
  ## Programming Language Preferences
 1. Python dominated as the most popular language across all experience levels.
 2. SQL was commonly used alongside Python, highlighting its importance in data handling.
 3. C++ is also used mostly by Students.
  ## Machine Learning Framework Usage
  1. TensorFlow was the second most used framework, primarily adopted by users with 1 to 3 years of experience.
  2. Keras, while also popular, had fewer users compared to TensorFlow and was mostly used by those with less than 3 years of experience.
  3. Scikit-learn remained one of the most widely used frameworks across all experience levels.
 
# Future work
In the future, this project could be expanded by adding more data from other surveys or reports to compare trends over time. We could also analyze people's opinions on the frameworks and languages they use. It would be interesting to look deeper into how well popular frameworks perform based on user experience. Also, analysis on specific job titles or exploring a specific subcategory in detail can help in coming up with useful insights. If anything we learned from this analysis, it's that we could have narrowed down the analysis to some categories since our audience is interested in specific parts of this survey.

# How to run the codes
simply copy and paste the code and run it. You can find the notebook attatched and there are comments on which approaches we used and why those approaches were used.

# Acknowledgments/References
I would like to express my sincere gratitude to my instructors for their invaluable guidance and support throughout this project. Their expertise and encouragement have greatly enhanced my learning experience. I would also like to thank my project partner for their collaboration, hard work, and dedication. Working together has been a rewarding experience, and I truly appreciate their contributions to making this project successful. Thank you all for your continuous support and for helping me grow professionally and academically.

