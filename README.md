# DataCamp Machine Learning Scientist Track

A sprint to complete and reproduce as much of the DataCamp ML Scientist Track as possible in 1 month for $1. Most of the material covered was introductory and a good refresher course for data scientists.

In this repo I've (tried!) to condense the code covered in the online environment, as well as the notes in the provided slides, into Jupyter notebooks for a handy reference. DataCamp did make it very difficult to extract data and internal functions out of their platform, hence only the code for the first 2 courses of the track are given here.

The completed courses are:

- [x] [1. Supervised Learning with scikit-learn](./1.%20Supervised%20Learning%20with%20scikit-learn): covers classification, regression, fune-tuning of models and preprocessing and pipelines.
- [x] [2. Unsupervised Learning in Python](./2.%20Unsupervised%20Learning%20in%20Python): covers clustering for dataset exploration, visualisation with hierarchical clustering and t-SNE, decorrelating your data and dimension reduction, and discovering interpretable features.
- [x] [3. Linear Classifiers in Python](./3.%20Linear%20Classifiers%20in%20Python): covers applying logistic regression and SVM, loss functions, logistic regression and support vector machines.

## Setup

Create the virtual environment:

```bash
python3 -m venv datacampenv
```

Activate the virtual environment:

```bash
source datacampenv/bin/activate
```

Install the dependencies into the environment:

```bash
(datacampenv) pip install -r requirements.txt
```

Install the Python execution backend for Jupyter (with same name as virtual environment):

```bash
(datacampenv) python -m ipykernel install --user --name=datacampenv
```

Run JupyterLab: 

```bash
(datacampenv) jupyter lab
```
