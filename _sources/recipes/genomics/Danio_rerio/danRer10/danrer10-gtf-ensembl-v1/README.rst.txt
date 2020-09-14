.. _`danrer10-gtf-ensembl-v1`:

danrer10-gtf-ensembl-v1
=======================

|downloads|

The GRCz10 gtf file from ensembl remapped to danRer10 (Any unmapped entries are removed from the file)

================================== ====================================
GGD Package                        danrer10-gtf-ensembl-v1 
Species                            Danio_rerio
Genome Build                       danRer10
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      yliu 
Data Provider                      NA
Data Version                       91
Genomic File Type                  NA
Data file coordinate basing        NA
Package's Data Files               NA
Approximate Size of Each Data File NA
Package Keywords                   gtf, gtf-file, ensembl
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Danio_rerio/danRer10/danrer10-gtf-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *False*. This package has not been set up to use the ``--prefix`` flag when running ggd install. Once installed, this package will work with other ggd tools that use ``--prefix`` flag.

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics danrer10-gtf-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/danrer10-gtf-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/danrer10-gtf-ensembl-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.