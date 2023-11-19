========
TorchKGE
========

.. image:: https://graphs.telecom-paristech.fr/images/logo_torchKGE_small.png
    :align: right
    :width: 100px
    :alt: logo torchkge

.. image:: https://img.shields.io/pypi/v/torchkge.svg
        :target: https://pypi.python.org/pypi/torchkge

.. image:: https://github.com/torchkge-team/torchkge/actions/workflows/ci_checks.yml/badge.svg
        :target: https://github.com/torchkge-team/torchkge/actions/workflows/ci_checks.yml

.. image:: https://readthedocs.org/projects/torchkge/badge/?version=latest
    :target: https://torchkge.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. image:: https://img.shields.io/pypi/pyversions/torchkge.svg
        :target: https://pypi.org/project/torchkge/

TorchKGE: Knowledge Graph embedding in Python and Pytorch.

TorchKGE is a Python module for knowledge graph (KG) embedding relying solely on Pytorch. This package provides
researchers and engineers with a clean and efficient API to design and test new models. It features a KG data structure,
simple model interfaces and modules for negative sampling and model evaluation. Its main strength is a highly efficient
evaluation module for the  link prediction task,  a central application of KG embedding. It has been `observed <https://torchkge.readthedocs.io/en/latest/reference/evaluation.html>`_ to be up
to five times faster than `AmpliGraph <https://docs.ampligraph.org/>`_ and twenty-four times faster than
`OpenKE <https://github.com/thunlp/OpenKE>`_. Various KG embedding models are also already implemented. Special
attention has been paid to code efficiency and simplicity, documentation and API consistency. It is distributed using
PyPI under BSD license.

Citations
---------
If you find this code useful in your research, please consider citing our `paper <https://arxiv.org/abs/2009.02963>`_ (presented at `IWKG-KDD <https://suitclub.ischool.utexas.edu/IWKG_KDD2020/index.html>`_ 2020):

.. code::

    @inproceedings{arm2020torchkge,
        title={TorchKGE: Knowledge Graph Embedding in Python and PyTorch},
        author={Armand Boschin},
        year={2020},
        month={Aug},
        booktitle={International Workshop on Knowledge Graph: Mining Knowledge Graph for Deep Insights},
    }

* Free software: BSD license
* Documentation: https://torchkge.readthedocs.io.
