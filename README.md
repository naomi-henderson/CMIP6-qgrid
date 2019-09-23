# CMIP6-qgrid
Jupyter notebook demonstrating the use of qgrid for data exploration in the Pangeo google cloud CMIP6 data collection

We are having a lot of problems using [Qqrid](https://github.com/quantopian/qgrid) on our newer kernels
- temporary fix, but no solution, see [#261](https://github.com/quantopian/qgrid/issues/261)
- essentially you must:
```
pip install qgrid
git clone --depth=1 https://github.com/qzchenwl/qgrid qgrid.git
jupyter labextension install qgrid.git/js/
```

Try it here:

JupyterHub:

- binder.pangeo.io: [![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/naomi-henderson/CMIP6-qgrid/master)


or

Classic Jupyter Notebook at mybinder.org:

- mybinder.org:     [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/naomi-henderson/CMIP6-qgrid/master)

N.B. qgrid does not seem to work with ipywidgets 7.5, so might need to:
- conda install ipywidgets=7.4.2

If you still have trouble (like on `ocean.pangeo.io`), try the following:

For a much more basic test, go to [basic_test_widget](https://github.com/AaronWatters/basic_test_widget) , follow the development installation and test a basic widget.  This does not work on `ocean.pangeo.io`
