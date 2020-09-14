.. _`grch37-liftover-chain-38-to-37-ensembl-v1`:

grch37-liftover-chain-38-to-37-ensembl-v1
=========================================

|downloads|

Liftover chain file from ensembl

================================== ====================================
GGD Package                        grch37-liftover-chain-38-to-37-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      ensembl
Data Version                       1
Genomic File Type                  chain.gz
Data file coordinate basing        NA
Package's Data Files               grch37-liftover-chain-38-to-37-ensembl-v1.chain.gz
Approximate Size of Each Data File grch37-liftover-chain-38-to-37-ensembl-v1.chain.gz: **730.39K**
Package Keywords                   chain, liftover, grch38, grch37, ensembl
Package Dependencies:              
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-liftover-chain-38-to-37-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-liftover-chain-38-to-37-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-liftover-chain-38-to-37-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-liftover-chain-38-to-37-ensembl-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.