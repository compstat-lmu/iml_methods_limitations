# Seminar on Limitations of Interpretable Machine Learning Methods

This project explains the limitations of current approaches in interpretable machine learning, such as partial dependence plots (PDP, Accumulated Local Effects (ALE), permutation feature importance, leave-one-covariate out (LOCO) and local interpretable model-agnostic explanations (LIME).
All of those methods can be used to explain the behavior and predictions of trained machine learning models.
The interpretation methods might not work well in the following cases:

- if a model models interactions (e.g. when a random forest is used)
- if features strongly correlate with each other
- if the model does not correctly model causal relationships
- if parameters of the interpretation method are not set correctly

## Get started

Step 0: Prerequisites

Make sure you have git and R up and running on your computer.

Step 1: Fork the repository on Github

Step 2: Clone the repository to your machine

Either use RStudio or the terminal

```
git clone git@github.com:compstat-lmu/iml_methods_limitations.git
```

Step 3: Install dependencies

Start R in the project folder:

```
install.packages("devtools")
devtools::install_dev_deps()
```

## Workflow


If you need some package, please also add it in the DESCRIPTION file.


## How to cite stuff
Put bib file into book.bib


https://bookdown.org/yihui/bookdown/
