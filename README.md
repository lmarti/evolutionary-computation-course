# [Evolutionary Computation with Jupyter/IPython](http://lmarti.github.io/evolutionary-computation-course/)
*Jupyter/IPython notebooks about genetic and evolutionary computation*

Luis Martí -- http://lmarti.com

This repository contains the Jupyter/IPython notebooks used in the demonstration classes of my course ["Advanced Evolutionary Computation: Theory and Practice"](http://lmarti.com/aec-2014), which I taught as part of the PhD in Electrical Engineering, [Department of Electrical Engineering](http://www.ele.puc-rio.br/) of the [Pontifícia Universidade Católica do Rio de Janeiro](http://www.puc-rio.br/).

**Note:** Although I am not currently giving this course I am updating the notebooks from time to time to meet software updates and remove bugs.

## Available notebooks

* [AEC.01 - A Fast (and Furious) Introduction to Python.ipynb](http://nbviewer.jupyter.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.01%20-%20A%20Fast%20%28and%20Furious%29%20Introduction%20to%20Python.ipynb)
* [AEC.02 - Elements of Evolutionary Algorithms.ipynb](http://nbviewer.jupyter.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.02%20-%20Elements%20of%20Evolutionary%20Algorithms.ipynb)
* [AEC.03 - Solving the TSP with GAs.ipynb](http://nbviewer.jupyter.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.03%20-%20Solving%20the%20TSP%20with%20GAs.ipynb)
* [AEC.04 - Evolutionary Strategies and Covariance Matrix Adaptation.ipynb](http://nbviewer.jupyter.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.04%20-%20Evolutionary%20Strategies%20and%20Covariance%20Matrix%20Adaptation.ipynb)
* [AEC.06 - Evolutionary Multi-Objective Optimization.ipynb](http://nbviewer.jupyter.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.06%20-%20Evolutionary%20Multi-Objective%20Optimization.ipynb)

## A note on viewing the notebooks

These notebooks are meant to be viewed as slides. That is why they contain relatively few text and mostly graphical information. However, nothing stops you from viewing them as regular notebooks. Note that `nbviewer` allows you to switch the notebooks "slides" mode.

![Click to view as slides](https://raw.githubusercontent.com/lmarti/jupyter_custom/master/imgs/view-as-slides.png)

## Offline (local) slides

* You can convert them to slides and view them locally by using `nbconvert` with a command like:

```
$ jupyter nbconvert --to slides --post serve <a-notebook-name.ipynb>
```
