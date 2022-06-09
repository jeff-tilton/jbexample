# Intro

This is a Jupyter Book example to show that Bokeh plots often do not work once a cell tag is used.  Results can be seen [here](https://jeff-tilton.github.io/jbexample/intro.html).

## Quickstart


```bash
$ git clone https://github.com/jeff-tilton/jbexample.git
$ cd jbexample
$ conda create -n jbenv python=3 
$ conda activate jbenv
$ conda install -c conda-forge jupyter-book
$ conda install bokeh
$ jupyter-book build .
```