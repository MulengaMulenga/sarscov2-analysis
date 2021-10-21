# sarscov2-analysis
Contains a collection of bioinformatics analysis for sarscov2 and plasmodium falciparum sequencing set up
## Getting started

In order to get started you will have to install `git` and `conda`. 

1. Go [here](https://git-scm.com/downloads) and follow the installation instructions appropriate for your operating system to install `git`.
2. Go [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html) to download `conda`. I would recommend downloading the `Miniconda` version that is appropriate for your operating system. Choose the version that uses Python 3.

Once you have completed steps 1. and 2., you should be able to clone this repository and install the conda environment. Using terminal, navigate to a folder where you keep your bioinformatics projects. Then type:

```
git clone https://github.com/MulengaMulenga/sarscov2-analysis.git
cd sarscov2-analysis
conda env create
```

Now you will have download all the code and installed all the dependencies required for analysis

## Running `Jupyter Notebook`

[Jupyter Notebook](https://jupyter.org/) is a great tool for exploratory data analyses. It allows you to combine blocks of code, plots, and text and equations (via markdown) into a single file called a "notebook" (more information [here](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html)). To launch `jupyter notebook`, navigate to the `nomads-workshop` directory and then type the following in your terminal:

```
conda activate sarscov
jupyter notebook
```

A new window should open in your internet browser, allowing you to navigate the directory and open the notebooks that are stored in the `/notebooks` directory.
