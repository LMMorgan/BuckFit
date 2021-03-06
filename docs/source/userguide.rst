Userguides
---------- 

These userguides cover building a training set and going through setting up the inputs for the fit and the different parameters which can be set. Following this, there are notebooks which show how to plot the forces, stress tensors, and errors for multiple fits, run a cross-validation, and check the lattice parameters against a reference.

An overview of the capabilities of ``PopOff``, with example inputs for running the code and varying the simulation conditions can be found in::

    popoff/userguides/README.md

Notebooks
^^^^^^^^^

Interactive versions of each notebook can be viewed using a `Jupyter notebook <http://jupyter-notebook.readthedocs.io/en/latest/#>`_, or viewed using `nbviewer <https://nbviewer.jupyter.org>`_ by following each (`nbviewer`) link.

#. `training_set <https://github.com/LMMorgan/PopOff/blob/master/userguides/training_set.ipynb>`_ (`nbviewer <https://nbviewer.jupyter.org/github/LMMorgan/PopOff/blob/master/userguides/training_set.ipynb>`_)
#. `fitting <https://github.com/LMMorgan/PopOff/blob/master/userguides/fitting.ipynb>`_ (`nbviewer <https://nbviewer.jupyter.org/github/LMMorgan/PopOff/blob/master/userguides/fitting.ipynb>`_)
#. `plotting <https://github.com/LMMorgan/PopOff/blob/master/userguides/plotting.ipynb>`_ (`nbviewer <https://nbviewer.jupyter.org/github/LMMorgan/PopOff/blob/master/userguides/plotting.ipynb>`_)
#. `lattice_parameters <https://github.com/LMMorgan/PopOff/blob/master/userguides/lattice_parameters.ipynb>`_ (`nbviewer <https://nbviewer.jupyter.org/github/LMMorgan/PopOff/blob/master/userguides/lattice_parameters.ipynb>`_)
#. `cross-validation <https://github.com/LMMorgan/PopOff/blob/master/userguides/cross-validation.ipynb>`_ (`nbviewer <https://nbviewer.jupyter.org/github/LMMorgan/PopOff/blob/master/userguides/cross-validation.ipynb>`_)


Running PopOff
---------------

Once the `dependencies <https://popoff.readthedocs.io/en/latest/installation.html>`_ and ``PopOff`` has been installed, the code can be run either through a python script or using a `Jupyter notebook <http://jupyter-notebook.readthedocs.io/en/latest/#>`_. An overview of the capabilities of ``PopOff``, with examples for running the code and varying the fitting parameters ca be found in::

   popoff/userguides/fitting.ipynb
   popoff/userguides/fitting.py

or the Jupyter notebook and python scripy can be found on GitHub `here <https://github.com/LMMorgan/PopOff/tree/master/userguides>`_.

The notebook or python script must be executed from the main directory and the training set must be located in ``vaspruns`` and formatted as ``vasprunX.xml`` where ``X`` increases sequentially from 0, i.e. ``vasprun0.xml``, ``vasprun1.xml``, ``vasprun2.xml``, etc.
