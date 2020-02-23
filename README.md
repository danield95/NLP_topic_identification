# Topic identification using the Latent Dirichlet allocation algorithm

This project implements NLP methodologies for cleaning, processing and modelling posts from a medical forum on the internet.

#### -- Project Status: [Completed]

## Project Description/Objective

The purpose of this project is to group posts by topics, and find what people are talking about.

### Methods Used
* The Latent Dirichlet allocation algorithm is being used.
* Implementation in Gensim and Mallet libraries. 

### Technologies
* Python
* Jupyter Notebook
* NLTK
* Gensim
* Pandas
* Numpy
* pyLDAvis

## Data
* Data can be accessed at `posts_sample.xlsx`
* Data in tabular format: superparent, id (unique for each body), main_post (1 for the fist post in a conversation, 0 for responses), datecreated (date in which the post has been created), title, body (contains all posts)

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).

2. Make sue you have installed all the libraries needed for this project. Those can be found at `requirements.txt`.

3. Raw data is being kept at `posts_sample.xlsx`

3. Implementation using the Gensim library `Gensim.ipynb`.

4. Implementation using the Mallet library `Mallet.ipynb`.
