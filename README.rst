Quantum Machine Learning Toolbox (qmlt)
###########################################

The Quantum Machine Learning Toolbox (QMLT) is a `Strawberry Fields <https://github.com/XanaduAI/strawberryfields>`_ application that simplifies the optimization of variational quantum circuits. Tasks for the QMLT range from variational eigensolvers and unitary learning to supervised and unsupervised machine learning with models based on a variational circuit.


Features
========


The Quantum Machine Learning Toolbox supports:

* The training of user-provided variational circuits

* Automatic and numerical differentiation methods to compute gradients of circuit outputs

* Optimization, supervised and unsupervised learning tasks

* Regularization of circuit parameters

* Logging of training results

* Monitoring and visualization of training through matplotlib and TensorBoard

* Saving and restoring trained models

* Parallel computation/GPU usage for TensorFlow-based models


Installation
============

Installation of SFOpenBoson, as well as all required Python packages mentioned above, can be done using pip:
::

    $ python -m pip install qmlt


Code authors
============

Maria Schuld and Josh Izaac.

If you are doing research using Strawberry Fields, please cite `our whitepaper <https://arxiv.org/abs/1804.03159>`_ and the QMLT documentation:

  Nathan Killoran, Josh Izaac, Nicolás Quesada, Ville Bergholm, Matthew Amy, and Christian Weedbrook. Strawberry Fields: A Software Platform for Photonic Quantum Computing. *arXiv*, 2018. arXiv:1804.03159

  Maria Schuld and Josh Izaac. Xanadu Quantum Machine Learning Toolbox documentation. https://qmlt.readthedocs.io.


Support
=======

- **Source Code:** https://github.com/XanaduAI/QMLT
- **Issue Tracker:** https://github.com/XanaduAI/QMLT/issues

If you are having issues, please let us know by posting the issue on our Github issue tracker.

We also have a `Strawberry Fields Slack channel <https://u.strawberryfields.ai/slack>`_ -
come join the discussion and chat with our Strawberry Fields team.


License
=======

QMLT is **free** and **open source**, released under the Apache License, Version 2.0.