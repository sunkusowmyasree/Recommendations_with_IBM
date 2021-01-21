# Recommendations_with_IBM

## Table of Contents
1. [Description](#description)
2. [Installing](#installing)
3. [Project Tasks](#Project Tasks)
4. [File Structure](#File Structure)
3. [Authors](#authors)
4. [License](#license)
5. [Acknowledgement](#acknowledgement)

<a name="descripton"></a>
## Description

This Project is a part of Data Science Nanodegree Program by Udacity in collaboration with IBM.
The dataset is provided by IBM taken directly from the IBM Watson Studio platform.. 
The aim of the project is to build a Recommendation system based which can recommend articles to any user and improve the user-article interactions on the platform.

<a name="installing"></a>
### Installing
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

<a name="Project Tasks"></a>
### Project Tasks
Your project will be divided into the following tasks

#I. Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

#II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

#III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

#IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

#V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

<a name="File Structure"></a>
### File Structure

* `data` folder contains the following:
    * `articles_community.csv`: contains the articles data csv file
    * `user-item-interactions.csv`: contains the User-Item Interactions csv file
	
* `img` folder contains the following:
    * `Dashboard.jpeg`: contains the Dashboard page of IBM Watson studio platform
	
* `Recommendations_with_IBM.html` : HTML page for this project
  
* `Recommendations_with_IBM.ipynb ` : Jupyter notebook with python codes

* `user_item_matrix.p` : pickle file of User-Item matrix

* `project_tests.py ` :  Test cases of this project

* `top_10.p` : Top 10 list for recommendation

* `top_20.p` : Top 20 list for recommendation

* `top_5.p` : Top 5 list for recommendation


<a name="authors"></a>
## Authors

* [Sowmya](https://github.com/sunkusowmyasree/)

<a name="license"></a>

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

<a name="acknowledgement"></a>

## Acknowledgements

* [Udacity](https://www.udacity.com/) for providing such a complete Data Science Nanodegree Program
* [IBM ](https://www.ibm.com/cloud/watson-studio) for providing Articles dataset 
