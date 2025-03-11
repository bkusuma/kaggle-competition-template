# Kaggle Competition Template

Here is a template you can use for managing your work and submissions for [Kaggle competitions](https://www.kaggle.com/competitions).

This project is based on the [kaggle_filestructure](https://github.com/mikezawitkowski/kaggle_filestructure) repository from [mikezawitkowski](https://github.com/mikezawitkowski) but with tweaks by me, an increased folder depth, and, most importantly, the ability to ["Create a new repository"](https://github.com/new?template_name=kaggle-competition-template&template_owner=bkusuma) using this template!

## Directory Structure

```markdown
.. 
└── kaggle
     ├── input                      <- data files for the competition 
     │    └── {competition-slug}
     │          ├── train.csv       <- example data
     │          └── test.csv        <- example data
     ├── src                        <- source scripts
     ├── working                    <- the working directory
     │       ├── notebook.ipynb     <- example Jupyter notebook
     │       └── submission.csv     <- example submission
     ├── Original_README.md         <- from kaggle.com/competitions/predict-west-nile-virus
     └── README.md                  <- what you're reading right now
```

## [Creating a repository from a template](#creating-a-repository-from-a-template)

- Above the file list, click **Use this template**.
- Then, select **Create a new repository**.

![Screenshot of the "Use this template" button and the dropdown menu expanded to show the "Open in a codespace" option.](https://docs.github.com/assets/cb-76823/images/help/repository/use-this-template-button.png)

- After using the template and cloning the repo, replace _{competition-slug}_ in the input directory with the slug from the competition you're working on
  - e.g. for [kaggle.com/competitions/`titanic`](https://www.kaggle.com/competitions/`titanic`), the slug would be "titanic"  
  - also upload the competition data to this folder  
- Since the GitHub structure doesn't perfectly line up with Kaggle's, you will need to add "`..`" preceding filepaths in code from Kaggle notebooks
  - e.g. `'/kaggle/input/titanic/train.csv'` from a Kaggle notebook becomes `'../kaggle/input/titanic/train.csv'` for a Jupyter notebook in the "working" directory.

****

### A copy of the [Original_README](https://github.com/bkusuma/kaggle-competition-template/blob/main/Original_README.md) is in the repository as well but please note it was last updated 2015/05/04

****
