# :rocket: Data Science Projects

This is a collection of Data Science projects for learning and exploration purposes. The projects are organized and grouped by subject/topic covering different approaches, algorithms and data-sets. Each project consists of a *Jupyter notebook* and, it has its own folder under the `notebooks` folder.

---

> :warning: This repository contains code and models experiments and are not production-ready, reusable, optimised and fine-tuned code and models. This is rather a sandbox or a playground for learning and trying different data science, machine learning techniques and approaches. Models might not perform well, and there is a place for overfitting/underfitting.

**Acknowledgements:** This repository was originally inspired by [:robot: Interactive Machine Learning Experiments](https://github.com/trekhleb/machine-learning-experiments).

## Projects

Projects were built using different libraries and tools, and the most used were [pandas](https://pandas.pydata.org/), [scikit-learn](https://scikit-learn.org) and [Tensorflow 2](https://www.tensorflow.org/) with [Keras](https://www.tensorflow.org/guide/keras/overview) API. The dependencies for each project is included in a `requirements.txt` file, for projects where the data-sets were auto-generated or scraped, a `data` folder is present.

**Blog:** For some projects, I have written a dedicated blog post on my website. The projects with a blog post have an :memo: icon link next to the project name.


### Supervised Learning

<table>
  <thead>
    <th width="150" style="width: 150px !important">&nbsp;</th>
    <th width="200" style="width: 200px !important">Project</th>
    <th width="150" style="width: 150px !important">Notebook</th>
    <th width="150" style="width: 150px !important">Tags</th>
    <th width="150" style="width: 150px !important">Dataset</th>
  </thead>
  <tbody>
    <tr>
      <td width="150"><img src="assets/titanic.jpg" alt="Titanic" width="150" /></td>
      <td width="200"><a href="notebooks/titanic">Titanic: Machine Learning from Disaster</a>
      <a href="https://hmatalonga.com/blog/kaggle-titanic-challenge" target="_blank">:memo:</a></td>
      <td>
        <a href="https://mybinder.org/v2/gh/hmatalonga/kaggle-titanic/master?filepath=notebooks/titanic/titanic.ipynb">
          <img src="https://mybinder.org/badge_logo.svg" alt="Binder">
        </a></br>
        <a href="https://colab.research.google.com/github/hmatalonga/data-science-projects/blob/master/notebooks/titanic/titanic.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
      <td width="150">
        <code>Classification</code>
      </td>
      <td width="150"><a href="https://www.kaggle.com/c/titanic/data">Titanic</a></td>
    </tr>
    <tr>
      <td width="150"><img src="assets/credit-card.jpg" alt="Credit Card Fraud Detection" width="150" /></td>
      <td width="200"><a href="notebooks/credit-card">Credit Card Fraud Detection</a>
      <a href="https://hmatalonga.com/blog/handling-imbalanced-datasets-fraud-detection" target="_blank">:memo:</a></td>
      <td>
        <a href="https://mybinder.org/v2/gh/hmatalonga/data-science-projects/master?filepath=notebooks/credit-card/credit-card.ipynb">
          <img src="https://mybinder.org/badge_logo.svg" alt="Binder">
        </a></br>
        <a href="https://colab.research.google.com/github/hmatalonga/data-science-projects/blob/master/notebooks/credit-card/credit-card.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
      <td width="150">
        <code>Imbalanced Classification</code>
      </td>
      <td width="150"><a href="https://www.kaggle.com/mlg-ulb/creditcardfraud/data">Credit Card Fraud Detection</a></td>
    </tr>
  </tbody>
</table>

<!-- ### Unsupervised Learning -->

<!-- ### Reinforcement Learning -->

<!-- ### Statistics -->

<!-- ### Exploratory Data Analysis -->

<!-- <table>
  <thead>
    <th width="150" style="width: 150px !important">&nbsp;</th>
    <th width="200" style="width: 200px !important">Project</th>
    <th width="150" style="width: 150px !important">Notebook</th>
    <th width="150" style="width: 150px !important">Tags</th>
    <th width="150" style="width: 150px !important">Dataset</th>
  </thead>
  <tbody>
    <tr>
      <td width="150"><img src="assets/palmerpenguins.jpg" alt="palmerpenguins" width="150" /></td>
      <td width="200"><a href="notebooks/palmerpenguins/palmerpenguins.ipynb">Palmer Antarctica Penguins (EDA)</a></td>
      <td>
        <a href="https://mybinder.org/v2/gh/hmatalonga/kaggle-titanic/master?filepath=notebooks/palmerpenguins/palmerpenguins.ipynb">
          <img src="https://mybinder.org/badge_logo.svg" alt="Binder">
        </a></br>
        <a href="https://colab.research.google.com/github/hmatalonga/data-science-projects/blob/master/notebooks/palmerpenguins/palmerpenguins.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
      <td width="150">
        <code>Data Visualization</code>
      </td>
      <td width="150"><a href="https://allisonhorst.github.io/palmerpenguins/index.html">palmerpenguins</a></td>
    </tr>
  </tbody>
</table> -->

<!-- ### Natural Language Processing -->

<!-- ### Recommender Systems -->

<!-- ### Others  -->

<!-- ### Competitions -->

## Setup

To run the repository locally, I suggest using docker to launch a [Jupyter Notebook](https://jupyter.org/) server.

It is based on the [jupyter/tensorflow-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-tensorflow-notebook), which includes popular packages from the scientific Python ecosystem.

### Requirements

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Launch Jupyter Server

Run Jupyter with `docker-compose` and open the link shown on your terminal (something like [http://localhost:8888](http://localhost:8888)).

```shell
$ docker-compose up
```

The projects will be available under the `notebooks` folder.

### Configuration

Feel free to change any settings of the Jupyter Notebook server by editing the `docker-compose.yml` file.

## Articles

- [:credit_card: Handling Imbalanced Datasets: Fraud Detection Study Case](https://hmatalonga.com/blog/handling-imbalanced-datasets-fraud-detection)
- [:ship: Predicting the Outcome of the Titanic Passengers](https://hmatalonga.com/blog/kaggle-titanic-challenge)
