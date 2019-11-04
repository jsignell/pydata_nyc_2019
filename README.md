# PyData NYC 2019

This repository is intended to be a launching-off point, not a source of code.
The code that we'll be looking at is in https://github.com/ContinuumIO/anaconda-package-data and https://github.com/jsignell/heat_and_trees.

### Run locally

```bash
conda env create --file binder/environment.yml
conda activate pydata_nyc_2019
jupyter notebook
```

If you want to use jupyterlab instead of `jupyter notebook` run:

```bash
conda install -c conda-forge jupyterlab
jupyter labextension install @pyviz/jupyterlab_pyviz
jupyter lab
```

### About me

I am a software developer at Anaconda Inc. currently working on developing best
practices for Python-using earth scientists. I work on visualization tools within the
[HoloViz ecosystem](https://holoviz.org) and data ingestion and analysis tools in the
broader PyData world. I live in Philadelphia and previously did hydrology research at
Princeton - studying lightning and rain patterns, water movement through the landscape,
and streamflow.
