.. _api_reference:


###
API
###


The `miblab` python package provides an API to *miblab* functionality
that is relevant across applications such as retrieving data or 
models, generating pdf reports, or deploying pipelines.

This page provides an API reference guide for the package. 

.. currentmodule:: miblab


.. raw:: html

    <h2 class="highlight-title">Reporting</h2>


To access these functions, miblab must be installed with the `report` option:

.. code-block:: console

   pip install miblab[report]

All reporting functionality is wrapped up in a single class:

.. autosummary::
   :toctree: ./api/
   :template: custom-class-template.rst

   Report


.. raw:: html

    <h2 class="highlight-title">Data</h2>

To access these functions, miblab must be installed with the `data` option:

.. code-block:: console

   pip install miblab[data]

APIs for upload and download to 
`Zenodo <https://zenodo.org/communities/miblab>`_ 
and 
`OSF <https://osf.io/un5ct/>`_:


.. autosummary::
   :toctree: ./api/
   :template: autosummary.rst

   zenodo_fetch
   osf_fetch
   osf_upload
   rat_fetch


.. raw:: html

    <h2 class="highlight-title">Deep-learning API</h2>

To access these functions, miblab must be installed with the `dlseg` option:

.. code-block:: console

   pip install miblab[dlseg]

Interfaces for deploying deep learning models.

.. autosummary::
   :toctree: ./api/
   :template: autosummary.rst

   totseg
   kidney_pc_dixon

.. currentmodule:: miblab_dl

The `miblab[dlseg]` option will be deprecated in future versions and all 
deep-learning models will be available via a dedicated package `miblab-dl`. 
At the moment this provides an API for the fat-water calculations:

.. code-block:: console

   pip install miblab-dl

.. autosummary::
   :toctree: ./api/
   :template: autosummary.rst

   fatwater
   
