# Examples of implementations for metrics

Notebooks, built on top of data collected by Perceval,
for illustrating how to compute metrics:

* [Code Commits](Code_Commits.ipynb),
includes the generation of file [git-commits.json],
with a Perceval dump of a git repository, as a data source.

# How to run the notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chaoss/wg-gmd/master?filepath=implementations)

You can run the notebooks directly in [Binder](https://mybinder.org):
Just click on the "launch binder" logo.

You can also run the notebooks locally on your computer.
For that, you need a Python3 environment with certain modules installed
(it is recommendable to use a virtual environment,
  see [Creation of virtual environments](https://docs.python.org/3/library/venv.html)).
To install the modules, just use pip3:

```bash
$ pip install jupyter
$ pip install pandas
$ pip install perceval
```

(check at the beginning of each notebook just in case more modules need to be installed).

Clone this repository and change directory to where this notebook resides:

```
$ git clone https://github.com/chaoss/wg-gmd
$ cd wg-gmd/implementations
```

Then launch Jupyter from the command line...

```
$ jupyter notebook
```

This will launch the Jupyter kernel, and will open your default browser
with the directory with all the notebooks loaded.
Click on the notebook you want to run, and you're ready to go.
More detailed instructions can be found in
[Introducing the Notebook Server’s Command Line Options](https://jupyter-notebook.readthedocs.io/en/stable/config.html).

Once you have the notebook in your browser, you can execute the selected cell
by clicking \[CTRL\]\[Enter\], or \[Shift\]\[Enter\]. In the latter case,
the current cell will be run, and the next one will be selected.
For selecting any cell, just click on it.

So, if you want to execute the whole dashboard, just select the first cell,
and click \[Shift\]\[Enter\] until you're done.
You can also click on the Cell menu, and select "Run All",
which will also run all the cells in the notebook.
More details can be found in [Executing a notebook](https://jupyter-notebook-beginner-guide.readthedocs.io/en/stable/execute.html#executing-a-notebook)

If you want to modify any cell, just click on it, look for the cursor,
and start writing.

If you want more details and context about Jupyter notebooks, have a look at
[Jupyter Notebook Tutorial](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook).
