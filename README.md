# SYXthDimension
Examine DX7 patches through dimension reduction (unsupervised learning)

There are so many DX7 patches available!  The notebook SYXthDimension.ipynb is aimed at grouping patches for the purpose of
* identifying identical (or nearly identical) patches, and
* exploring changes between similar patches.

## Background
The approach is to take some relevent subset of data from individual DX7 patches, take the resulting set of vectors and reduce to a 2D representation.  Manifold learning of [scikit-learn] (https://scikit-learn.org/stable/modules/manifold.html#manifold) is used.  The technique [t-SNE](https://lvdmaaten.github.io/tsne/) is used for dimensionality reduction, but other mehods in scikit-learn are certainly worth investigating.

## Packages used
* python-rtmidi
* scikit-learn
