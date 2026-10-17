**Python components for network neuroscience**

This is a development fork of `netneurotools <https://github.com/netneurolab/netneurotools>`__, a toolbox from McGill's Network Neuroscience Lab. Upstream provides dataset fetchers, empirical and surrogate network construction, graph metrics, statistics, and brain-network visualization. It is useful for connecting data preparation with network analysis in Python research workflows.

**Contribution to review:** `PR #186 <https://github.com/netneurolab/netneurotools/pull/186>`__ proposes an explicit extraction filter for downloaded TAR archives. The contribution concerns dataset retrieval and extraction; its implementation and review status are documented in the linked upstream proposal.

Begin with the `official documentation <https://netneurolab.github.io/netneurotools/>`__ for installation and examples. The original README explains version choices and preserves citation guidance for both the toolbox and redistributed datasets. The `branch comparison <https://github.com/netneurolab/netneurotools/compare/main...jdotc1:main>`__ shows this fork's default branch alongside upstream.

----

netneurotools: Tools for network neuroscience
=============================================

|

.. .. image:: https://zenodo.org/badge/375755159.svg
..    :target: https://zenodo.org/badge/latestdoi/375755159
..    :alt: Zenodo record

.. image:: https://img.shields.io/pypi/v/netneurotools
   :target: https://pypi.python.org/pypi/netneurotools/
   :alt: Latest PyPI version

.. image:: https://img.shields.io/badge/docker-netneurolab/netneurotools-brightgreen.svg?logo=docker&style=flat
  :target: https://hub.docker.com/r/netneurolab/netneurotools/tags/
  :alt: Latest Docker image

.. image:: https://github.com/netneurolab/netneurotools/actions/workflows/tests-basic.yml/badge.svg
  :target: https://github.com/netneurolab/netneurotools/actions/workflows/tests-basic.yml
  :alt: run-tests status

.. image:: https://github.com/netneurolab/netneurotools/actions/workflows/docs.yml/badge.svg
  :target: https://netneurolab.github.io/netneurotools/
  :alt: deploy-docs status

|

This toolbox is a collection of functions written in Python that get frequent
usage in the `Network Neuroscience Lab <https://netneurolab.github.io/>`_, housed in
the `Brain Imaging Centre <https://www.mcgill.ca/bic/home>`_ at
`McGill University <https://www.mcgill.ca/>`_.

The accompanying paper can be found on `bioRxiv <https://www.biorxiv.org/content/10.1101/2025.09.09.675160v1>`_.

.. _features:

Features
--------

Netneurotools provides a wide range of tools for network neuroscience research.

*  A range of useful datasets fetchers

*  Network construction: empirical and surrogate

*  Network (graph) metrics calculation: up-to-date and optimized

*  Brain and network visualization

*  Optimized statistics routines

*  Convenient interface for external tools

*  And much more!


Check out our `documentation <https://netneurolab.github.io/netneurotools/>`_
for more information!


.. _installation:

Installation
------------

You can install directly from PyPi with :code:`pip install netneurotools`.

This package is under active development. We recommend installing the latest version
with

.. code-block:: bash

    pip install git+https://github.com/netneurolab/netneurotools.git


If you are looking for the earlier version of the toolbox before the recent breaking changes,
you can install it with

.. code-block:: bash

    pip install git+https://github.com/netneurolab/netneurotools.git@0.2.X


.. _development:

Development
-----------

This package has been developed by members of the Network Neuroscience Lab in
pursuit of their research. While we've made every effort to ensure these tools
work and have some documentation, there is always room for improvement! If
you've found a bug, are experiencing a problem, or have a question, create a
new `issue <https://github.com/netneurolab/netneurotools/issues>`_ with some
information about it and one of our team members will do our best to help you.

.. _citation:

Citation
-----------

If you use the toolbox, please cite our `pre-print <https://www.biorxiv.org/content/10.1101/2025.09.09.675160v1>`_.

Importantly, ``netneurotools`` often implements and builds on tools that have
been previously developed, and we redistribute datasets that were acquired
elsewhere. If you use the toolbox, please also ensure proper attribution to the
original work, using the references found in the docstrings or in the
Reference API.

.. _licensing:

License Information
-------------------

This codebase is licensed under the 3-clause BSD license. The full license can
be found in the `LICENSE <https://github.com/netneurolab/netneurotools/blob/
master/LICENSE>`_ file in the ``netneurotools`` distribution.

All trademarks referenced herein are property of their respective holders.

.. |sparkles| replace:: ✨
