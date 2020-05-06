# Article_Recommendation_Systems
Studied data collections of user and article records to make rank-based, collaborative-based, and svd recommendations for users

## Table of Contents:
- [Installation](#installation)
- [Project Motivation](#project-motivation)
- [Data Descriptions](#data-descriptions)
- [File Descriptions](#file-descriptions)
- [Results](#results)
- [Licensing, Authors, Acknowledgements](#end)

## Installation
There is no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.

To test out parts of recommendations in the project, download the entire repository and open `Recommendations.ipynb` in Jupyter Notebook.

## Project Motivation
This project aims to analyze user-article interactions and recommend articles for existing and new users in the IBM Watson Studio.

## Data Descriptions
There is two .csv files available in the /data folder to perform the analysis:
- articles_community.csv: articles in the IBM Watson Studio community.
- user-item-interactions.csv: interaction between readers and articles based on reader email address.

## File Descriptions
There are one .ipynb file, one .py file, and four .p files available to achieve the above goals and test results:
- Recommendations.ipynb: the main file that realizes different recommendation methods.
- project_tests.py: a test file is used to check the validity of the functions and methods created in the .ipynb file.
- top_5.p, top_10.p, top_20.p, and user_item_matrix.p: result files that store results generated during recommendation.

## Results
In this project, I tested rank-based, collaborative-based, and SVD methods for article recommendation.
In order to further improve the recommendation model, retrieving more evaluation metrics and introducing A/B testing are highly recommended.
<a name="end"></a>
## Licensing, Authors, Acknowledgements
Credit goes to [IBM Watson](https://dataplatform.cloud.ibm.com/) for the data. The code is under open source GNU, feel free to use the code here as you would like!
