# :rocket: Data Science Projects

This is a collection of Data Science projects for learning and exploration purposes. The projects are organized and grouped by subject/topic covering different approaches, algorithms and data-sets. Each project consists of a *Jupyter notebook* and it has its own folder under the `notebooks` folder.

---

> :warning: This repository contains code and models experiments and are not production ready, reusable, optimised and fine-tuned code and models. This is rather a sandbox or a playground for learning and trying different data science, machine learning techniques and approaches. Models might not perform well and there is a place for overfitting/underfitting.

**Acknowledgements:** This repository was originally inspired by [:robot: Interactive Machine Learning Experiments](https://github.com/trekhleb/machine-learning-experiments).

## Projects

Projects were built using a combination of different libraries and tools and the most used were [pandas](https://pandas.pydata.org/), [scikit-learn](https://scikit-learn.org) and [Tensorflow 2](https://www.tensorflow.org/) with [Keras](https://www.tensorflow.org/guide/keras/overview) API. The dependencies for each project is included in a `requirements.txt` file. For projects where the data-sets were auto-generated or scraped a `data` folder is present.

**Blog:** For some projects I have written a dedicated blog post in my website. The projects with a blog post have a :memo: icon link next to the project name.

### Supervised Learning

|     | Project                                      | Notebook      | Tags             | Dataset    |
| --- | -------------------------------------------- | ------------- | ---------------- | ---------- |
| ![Titanic](assets/titanic.jpg) | [Titanic: Machine Learning from Disaster](notebooks/titanic/titanic.ipynb) [:memo:](https://hmatalonga.com/blog) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hmatalonga/data-science-projects/blob/master/notebooks/titanic/titanic.ipynb) | `Classification`, `Kaggle` | [Titanic](https://www.kaggle.com/c/titanic/data) |

<!-- ### Unsupervised Learning

### Reinforcement Learning

### Statistics

### Exploratory Data Analysis

### Natural Language Processing

### Recommender Systems

### Others 

### Competitions -->

## Setup

To run the repository locally, I suggest using docker to launch a [Jupyter Notebook](https://jupyter.org/) server.

### Requirements

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Launch Jupyter Server

Run Jupyter with `docker-compose` and open the link shown on your terminal (something like [http://localhost:8888](http://localhost:8888)).

```shell
$ docker-compose up
```

The projects will be available under `/home/jovyan` inside the container.

### Configuration

Feel free to change any settings of the Jupyter Notebook server by editting the `docker-compose.yml` file.
