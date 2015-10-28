Tock
====

Tock stands for Theory Of Computing toolKit. It can simulate the
automata taught in standard theory of computation courses
(deterministic and nondeterministic finite automata, pushdown
automata, and Turing machines). It also allows multiple cells, stacks,
or tapes, and look-ahead/behind.

The documentation is contained in a series of [IPython] notebooks:

- Introduction.pynb
- DFAs.pynb
- NFAs.pynb
- PDAs.pynb
- TMs.pynb

Installation
------------

In order to view these notebooks, you'll need [IPython] and
[GraphViz]. The easiest way to get them is:

1. Install [Miniconda]. Important: Select Python 2.7, not 3.x.
2. Install [IPython] by running `conda install jupyter`.
3. If you don't have [GraphViz] already, don't worry; Tock downloads
   and uses [Viz.js] instead.

Then, run `ipython notebook` in the Tock directory. A web browser
should open, showing you the contents of the directory. Click on one
of the `.pynb` files to view it.

[IPython]: http://ipython.org
[Miniconda]: http://conda.pydata.org/miniconda.html
[Graphviz]: http://www.graphviz.org
[Viz.js]: http://github.com/mdaines/viz.js/
