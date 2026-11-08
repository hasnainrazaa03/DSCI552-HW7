# DSCI 552 - Homework 7

Anuran Calls (MFCCs) data set: multi-class and multi-label classification with binary
relevance. Gaussian SVMs on raw and standardized attributes, L1-penalized linear SVMs with
and without SMOTE, a classifier chain, and multi-label confusion matrices, precision, recall
and ROC curves. K-means clustering with k chosen by the silhouette, the majority labels of
each cluster, and the Hamming distance, score and loss over 50 runs. Dendrograms for
ISLR 12.6.2. The extra practice problems (ISLR 12.6.1 and 12.6.3 to 12.6.13) are in a
second notebook.

Name: Mohammad Hasnain Raza
GitHub Username: hasnainrazaa03
USC ID: 1259246355

## Structure

```
data/anuran_calls/  Frogs_MFCCs.csv, Readme.txt
data/islr/          USArrests.csv, Boston.csv, Ch12Ex13.csv (used by the extra practice)
notebook/           Raza_MohammadHasnain_HW7.ipynb (the homework)
                    Raza_MohammadHasnain_HW7_Extra.ipynb (extra practice)
requirements.txt    package versions used
```

## Running the notebook

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cd notebook
jupyter notebook Raza_MohammadHasnain_HW7.ipynb
```

The notebooks read the data with relative paths such as `../data/anuran_calls/Frogs_MFCCs.csv`,
so they run from the `notebook` folder without any change. The homework notebook takes about
seven minutes to run and the extra practice notebook about one minute.
