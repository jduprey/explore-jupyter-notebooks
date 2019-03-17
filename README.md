# explore-jupyter-notebooks
Exploring Jupyter Notebooks

## Setting Up An Environment

```bash

## Start with a base conda environment 
$ nvm use v10.15.3 # you need nvm to install jupyterlab plugins
$ pyenv activate anaconda3-2018.12

## Then create an environment from scratch
$ conda create --name pynotebook2
## Or from environment.yml
$ conda env create -f environment.yml

$ conda activate pynotebook2

## This
$ conda install -c conda-forge jupyter jupyterlab ipywidgets bqplot
## Or This
$ conda update -f environment.yml

## Add extensions to Jupyter Lab
$ jupyter lab clean
$ jupyter labextension install @jupyter-widgets/jupyterlab-manager
$ jupyter labextension install bqplot
```

### References

- [Manage Conda Environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
- [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)
- [iPyWidgets](https://ipywidgets.readthedocs.io/en/stable/user_install.html)
- [BQPlot](https://github.com/bloomberg/bqplot)

