# KAR Global ML Roundtable - Dask

This tutorial was given at KAR Global's ML Roundtable on 2021-05-20. It is mostly populated with culled down work done by the Dask team for tutorials found in the following locations:

- https://github.com/dask/dask-tutorial
- https://github.com/jrbourbeau/hacking-dask
- https://github.com/adbreind/pycon2021-dask-sql

## Prepare

1\. Clone this repository:

```shell
git clone git@github.com:drewfustin/kar-roundtable-dask.git
```

2\. Install necessary packages using Conda:

```shell
conda env create -f environment.yml
conda activate kar-dask
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

3\. Launch Jupyter:

```shell
jupyter lab
```
