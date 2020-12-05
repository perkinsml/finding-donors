# Project Motivation
This project evaluates several supervised learning algorithms (including bagging, boosting and spatial algorithms) to train a model that can be used to identify potential donors to a fictitious charity (CharityML).  

After previously sending nearly 32,000 letters to people in the community to request donations, CharityML observed that every donation they received came from someone earning more than $50,000 annually.  To expand their potential donor base, CharityML has decided to launch a new funding campaign by sending a large number of letters to new, potential donors.  To optimise their spend, CharityML is seeking to target the people that are most likely to make a donation i.e. those people who earn more than $50,000 per year.

Trained with 1994 US census data, ML algorithms are used to predict people who are likely to earn more than $50,000 per year, enabling the charity to optimise the investment associated with requesting these donations by targeting people who are most likely to donate.  While it can be difficult to determine an individual's general income bracket directly from public sources, this project also identifies the census data fields that have the most predictive power in inferring whether a person earns more than $50,000 per year, enabling CharityML to target people with these characteristics. 

# File Descriptions
The notebook contains the code required to explore and prepare the census data for modeling.  It also contains the code required to train, evaluate and tune a range of supervised learning algorithms, and to examine the census data feature importance.  The visuals.py module contains a number of helper functions used in the finding_donors.ipynb Notebook.

# Installations
This notebook was developed using the library versions below:
* python: 3.7.6
* pandas: 1.0.1
* numpy: 1.16.4
* matploltlib: 3.1.2
* scikit-learn: 0.22.1

# Acknowledgments
Thank you to Udacity for designing this project as part of the Data Science Nanodegree.
