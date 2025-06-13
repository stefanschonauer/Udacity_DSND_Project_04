# Udacity Data Science Nanodegree

## Project 4 - Data Science Recommendation Systems

### Read Me

### Table of Contents

<ul>
<li><a href="#Installation">Installation</a></li>
<li><a href="#Project-Motivation">Project Motivation</a></li>
<li><a href="#File-Descriptions">File Descriptions</a></li>
<li><a href="#Results">Results</a></li>
<li><a href="#Licensing,-Authors,-Acknowledgements">Licensing</a></li>
</ul>

### Installation

This code was written by using Python, version 3.12.3 and the following libraries:

- scikit-learn
- pandas
- numpy
- matplotlib
- project_tests.

### Project Motivation

The fourth project of Udacity's Data Scientist Nanodegree starts with an

- **Exploratory Data Analysis**

and deals with recommendation systems like

- **Rank-Based Recommendations**,
- **User-User Collaborative Filtering**,
- **Content Based Recommendations**,
- **Matrix Factorization**.

### File Descriptions

There are seven relevant files in this repository:

- `starter/Recommendations_with_IBM.ipynb`: Jupyter Notebook including the data analysis and recommendation systems.
- `starter/project_tests`: file with several tests for checking and comparing interims results.
- `starter/top_5.p, top_10.p, top_20.p`: files used for checking and comparing interims results.
- `starter/data/user-item-interactions.csv`: Database.
- `LICENSE.txt`: Udacity's license declaration.

### Results

All used recommentation systems work different and have strengths and limitations.

**Rank-based recommendation systems** as example of knowledge-based recommendations systems work using filters. User provide information about types of recommendations they want and get the most relevant back. That is the reason why they work for new users and deal the cold start problem. In this example a user asks for articles and it get the most popular articles back.

**User-user based recommendation systems** as example of collaborative recommendations systems use connections between users. User get personalized recommendations based on other users interests and preferences. Therefore they need a user history and do not deal the cold start problem. In the given example user get recommendations by users with similar preferences instead of the article topic.

**Content-based recommendation systems** use similarities between items, so user get recommendations only based on item and content. For operations they do not need a user history and they deal the cold start problem. In the specific example user get recommendations based on similarity based on the current article.

**Matrix-factorization** uses latent factors. Latent factors are not directly observed in the data, but may be recognized when looking at relationsships and trends. This model works with less information and do not need a large user history. Because of the difficulty of observing latent factors, these systems have a lower interpretability.

Methods and ideas to **improve the recommendation systems** are
- adding more information using metrics like click-through rate (CTR) or Conversion Rate
- evaluation with A/B testing or
- check for and reduce the bias.

### Licensing, Authors, Acknowledgements

The project is originally designed by Udacity. Udacity's licence declaration you can find in the `LICENSE.txt` file.

Other sources and quotes in the Jupyter Notebook are mentioned on the relevant position.