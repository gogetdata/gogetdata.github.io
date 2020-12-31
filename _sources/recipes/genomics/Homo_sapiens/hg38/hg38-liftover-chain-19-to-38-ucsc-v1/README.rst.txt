.. _`hg38-liftover-chain-19-to-38-ucsc-v1`:

hg38-liftover-chain-19-to-38-ucsc-v1
====================================

|downloads|

Liftover chain file from UCSC

================================== ====================================
GGD Package                        hg38-liftover-chain-19-to-38-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      ucsc
Data Version                       1
Genomic File Type                  over.chain.gz
Data file coordinate basing        NA
Package's Data Files               hg38-liftover-chain-19-to-38-ucsc-v1.over.chain.gz
Approximate Size of Each Data File hg38-liftover-chain-19-to-38-ucsc-v1.over.chain.gz: **227.70K**
Package Keywords                   chain, liftover, hg38, hg19, ucsc
Package Dependencies:              htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-liftover-chain-19-to-38-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-liftover-chain-19-to-38-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-liftover-chain-19-to-38-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-liftover-chain-19-to-38-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.