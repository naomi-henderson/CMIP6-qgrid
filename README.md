# CMIP5-qgrid
Jupyter notebooks demonstrating the use of qgrid for data exploration in the Pangeo google cloud CMIP6 data collection

We are having a lot of problems using [Qqrid](https://github.com/quantopian/qgrid) on our newer kernels

Note, to add qgrid to your own JupyterLab/Hub kernel, see `Qgrid` [readthedocs](https://qgrid.readthedocs.io/en/latest/) or
the following should work if you are using conda:
- conda install -c conda-forge qgrid
- jupyter labextension install qgrid
- jupyter labextension install @jupyter-widgets/jupyterlab-manager@1.0

or, for Classic Notebook:
- jupyter nbextension enable --py --sys-prefix qgrid
- jupyter nbextension enable --py --sys-prefix widgetsnbextension

Try it here:

JupyterHub:
binder.pangeo.io: [![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/naomi-henderson/CMIP6-qgrid/master)
mybinder.org:     [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/naomi-henderson/CMIP6-qgrid/master?urlpath=lab)

or

Classic Jupyter Notebook at mybinder.org:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/naomi-henderson/CMIP6-qgrid/master)

