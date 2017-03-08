# [Evolutionary Computation with Jupyter/IPython](http://lmarti.github.io/evolutionary-computation-course/)
## Jupyter/IPython notebooks about genetic and evolutionary computation.

Luis Martí -- http://lmarti.com

This repository contains the Jupyter/IPython notebooks that were used in the demonstrations classes of my course [_"Advanced Evolutionary Computation: Theory and Practice"_](http://lmarti.com/aec-2014), which was taught as part of the PhD in Electrical Engineering, [Department of Electrical Engineering](http://www.ele.puc-rio.br/) of the [Pontifícia Universidade Católica do Rio de Janeiro](http://www.puc-rio.br/).

**Note:** Although I am not currently giving this course I am updating the notebooks from time to time.

Project web: http://lmarti.github.io/evolutionary-computation-course/

## Available notebooks

* [AEC.01 - A Fast (and Furious) Introduction to Python.ipynb](http://nbviewer.ipython.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.01%20-%20A%20Fast%20%28and%20Furious%29%20Introduction%20to%20Python.ipynb)
* [AEC.02 - Elements of Evolutionary Algorithms.ipynb](http://nbviewer.ipython.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.02%20-%20Elements%20of%20Evolutionary%20Algorithms.ipynb)
* [AEC.03 - Solving the TSP with GAs.ipynb](http://nbviewer.ipython.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.03%20-%20Solving%20the%20TSP%20with%20GAs.ipynb)
* [AEC.04 - Evolutionary Strategies and Covariance Matrix Adaptation.ipynb](http://nbviewer.ipython.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.04%20-%20Evolutionary%20Strategies%20and%20Covariance%20Matrix%20Adaptation.ipynb)
* [AEC.06 - Evolutionary Multi-Objective Optimization.ipynb](http://nbviewer.ipython.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.06%20-%20Evolutionary%20Multi-Objective%20Optimization.ipynb)

## A note on viewing the notebooks

Notebooks are meant to be viewed as slides. That is why they contain relatively few text and mostly graphical information. However, nothing stop you from viewing them as regular notebooks.

### Online viewing

Notebooks converted to static html slides:
* [AEC.01 - A Fast (and Furious) Introduction to Python](http://lmarti.github.io/evolutionary-computation-course/AEC.01%20-%20A%20Fast%20(and%20Furious)%20Introduction%20to%20Python.slides.html)
* [AEC.02 - Elements of Evolutionary Algorithms](http://lmarti.github.io/evolutionary-computation-course/AEC.02 - Elements of Evolutionary Algorithms.slides.html)
* [AEC.03 - Solving the TSP with GAs](http://lmarti.github.io/evolutionary-computation-course/AEC.03 - Solving the TSP with GAs.slides.html)
* [AEC.04 - Evolutionary Strategies and Covariance Matrix Adaptation](http://lmarti.github.io/evolutionary-computation-course/AEC.04 - Evolutionary Strategies and Covariance Matrix Adaptation.slides.html)
* [AEC.06 - Evolutionary Multi-Objective Optimization](http://lmarti.github.io/evolutionary-computation-course/AEC.06 - Evolutionary Multi-Objective Optimization.slides.html)

Another option is to use [nbviwer.jupyter.org](http://nbviwer.jupyter.org)).

### Offline (local) slides

* You can convert them to slides and view them locally by using `nbconvert` with a command like:

```
$ jupyter nbconvert --to slides --post serve <a-notebook-name.ipynb>
```

* Another -very cool- option is to install [Reveal.js - Jupyter/IPython Slideshow Extension](https://github.com/damianavila/live_reveal) for a (very cool) live view where you can actually execute the notebook in slide mode. This is the one I use in class.
