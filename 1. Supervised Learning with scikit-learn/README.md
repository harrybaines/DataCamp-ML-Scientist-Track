# Supervised Learning with scikit-learn

- [1. Classification](./1.%20Classification/):
	- k-Nearest neighbors classification
	- Train/test splits
	- Computing accuracy
	- Overfitting/underfitting 
- [2. Regression](./2.%20Regression/):
	- Creating features
	- Linear regression
	- Visualising linear regression
	- Multiple linear regression
	- Regression performance
	- Cross-validation for R-squared
	- Regularised regression: Ridge
	- Lasso regression for feature importance
- [3. Fune-Tuning Your Model](./3.%20Fine-Tuning%20Your%20Model/):
	- Classification metrics
	- Logistic regression and the ROC curve
	- Hyperparmater tuning
- [4. Preprocessing and Pipelines](./4.%20Preprocessing%20and%20Pipelines/):
	- Creating dummy variables
	- Missing values
	- Pipelines
	- Centering and scaling

This course was only $1 for a whole month and was a great refresher of fundamental machine learning concepts.

I decided to aggregate all the materials covered in the course and store them here for reference. For each chapter I've downloaded the code solutions for each exercise and put them all into Jupyter notebooks which you can find in each chapter. In some cases, DataCamp made it difficult to use the same dataset across exercises, so I had to export 
multiple versions of the same dataset (cheers DataCamp 😂).

I've also converted each notebook to PDF format:

```bash
jupyter nbconvert --to webpdf --allow-chromium-download NOTEBOOK_NAME.ipynb
``` 

and I've put all these output PDF's into a [master PDF](./all-notes.pdf) which you can easily CMD+F through to find stuff.
