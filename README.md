# DataCamp Machine Learning Scientist Track

- [1. Supervised Learning with scikit-learn](./1. Supervised Learning with scikit-learn): covers classification, regression, funr-tuning of models and preprocessing and pipelines.

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
