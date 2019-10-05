# Data Scientist Nanodegree
# Experimental Design & Recommendations
## Project: Recommendations with IBM

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/).

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html).

I recommend installing [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Code

The code has been created as part of the Udacity Data Scientist Nanodegree and is provided in the `Recommendations_with_IBM.ipynb` notebook file. The file `project_tests.py` is used as a test module.

### Run

In a terminal or command window, run one of the following commands:

```bash
jupyter notebook Recommendations_with_IBM.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data
The following datasets from IBM Watson Studio are used to provide recommendations:  
- `articles_community.csv`: provides information about the articles on the IBM Watson Studio platform,
- `user-item-interactions.csv`: provides information about the interactions between the users and articles on the IBM Watson Studio platform.

The goal is to study recommendation techniques which provide new articles to the users that are most pertinent to them. The articles are from the IBM Watson Studio platform. This platform provides tools for data scientists, application developers and subject matter experts to collaboratively and easily work with data to build and train models at scale.

The study will be structured into the following parts:
- Exploratory Data Analysis: gain basic understanding about the data,
- Rank Based Recommendations: find most popular articles based on the most interactions,
- User-User Based Collaborative Filtering: recommend articles from similar users,
- Matrix Factorization: machine learning approach to build recommendations.
