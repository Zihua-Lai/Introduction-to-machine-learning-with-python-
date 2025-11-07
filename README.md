# Introduction-to-machine-learning-with-python

This repository holds the code for the forthcoming book "Introduction to Machine
Learning with Python" by [Andreas Mueller](http://amueller.io) and [Sarah Guido](https://twitter.com/sarah_guido).
You can find details about the book on the [O'Reilly website](http://shop.oreilly.com/product/0636920030515.do).

The book requires the current stable version of scikit-learn, that is 0.20.0.  Most of the book can also be used with previous versions of scikit-learn, though you need to adjust the import for everything from the
``model_selection`` module, mostly ``cross_val_score``, ``train_test_split`` and ``GridSearchCV``.

All datasets are included in the repository, except the aclImdb dataset, which you can download from the page of [Andrew Maas](http://ai.stanford.edu/~amaas/data/sentiment/). See the book for details.
If you get ``ImportError: No module named mglearn`` you can try to install mglearn into your Python environment using The command ``pip install mglearn`` in your terminal or ``!pip install mglearn`` in Jupyter Notebook.
