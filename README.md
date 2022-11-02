# DataCamp Machine Learning Scientist Track

Update: DataCamp makes it difficult to extract data and internal functions out of their platform, hence only the first 3 courses of the track are given here

A great interactive, introductory and refresher online course for data science and ML enthusiasts. In this repo I've condensed the code covered in the online environment, as well as the notes in the provided slides, into Jupyter notebooks for a handy reference.

The completed courses so far are:

- [x] [1. Supervised Learning with scikit-learn](./1. Supervised Learning with scikit-learn): covers classification, regression, fune-tuning of models and preprocessing and pipelines.
- [x] [2. Unsupervised Learning in Python](./https://github.com/harrybaines/DataCamp-ML-Scientist-Track/tree/main/2.%20Unsupervised%20Learning%20in%20Python): covers clustering for dataset exploration, visualisation with hierarchical clustering and t-SNE, decorrelating your data and dimension reduction, and discovering interpretable features.
- [ ] [3. Linear Classifiers in Python](./https://github.com/harrybaines/datacamp-ml-scientist-track/tree/main/3.%20Linear%20Classifiers%20in%20Python): covers applying logistic regression and SVM, loss functions, logistic regression and support vector machines.

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
