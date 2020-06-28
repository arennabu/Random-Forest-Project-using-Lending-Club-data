# Random-Forest-Project-using-Lending-Club-data

### Introduction:
For this project, I will be exploring publicly available data from LendingClub.com. Lending Club connects people who need money (borrowers) with people who have money (investors). Hopefully, as an investor you would want to invest in people who showed a profile of having a high probability of paying you back. I will try to create a model that will help predict this.

Lending club had a very interesting year in 2016, so let's check out some of their data and keep the context in mind. This data is from before they even went public.

I will use lending data from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full.

### Install
`import pandas as pd`
`import numpy as np
`import matplotlib.pyplot as plt`
`import seaborn as sns`
`from sklearn.model_selection import train_test_split`
`from sklearn.ensemble import RandomForestClassifier`
`from sklearn.metrics import classification_report,confusion_matrix`
