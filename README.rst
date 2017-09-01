Wafermapper
===========

--------------------
**Wafermapper** - Bokeh based plotting library to plot test (single currently) 
results, as Heatmap, from individual chips to the wafer map.

--------------------

NOTE
----
- Early version developed as a jupyter notebook (within jupyter lab environment) 
using `Pipenv <https://github.com/kennethreitz/pipenv/>` and `JupyterLab <https://github.com/jupyterlab/jupyterlab>`.

Features
--------

- Supports multiple cell types.
- Currently supports only one test type per plot.
- Interactive and available offline (based on Bokeh)

Usage
-----

- Download code and change into the directory
- Assuming `Pipenv <https://github.com/kennethreitz/pipenv/>` and 
`JupyterLab <https://github.com/jupyterlab/jupyterlab>` are installed.
::
    $ pipenv install
    $ jupyter lab
::

In the session, open ``bokeh_plot_v1.ipynb`` and run all cells to see the output.

TODO
----

- Describe input format
- Restructure code to make the notebook more clear.