.. _`grch37-chromsizes-ggd-v1`:

grch37-chromsizes-ggd-v1
========================

|downloads|

Chromosome lengths for GRCh37

================================== ====================================
GGD Package                        grch37-chromsizes-ggd-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      arq5x 
Data Provider                      GGD
Data Version                       16-Apirl-2020
Genomic File Type                  txt
Data file coordinate basing        NA
Package's Data Files               grch37-chromsizes-ggd-v1.txt
Approximate Size of Each Data File grch37-chromsizes-ggd-v1.txt: **5.17K**
Package Keywords                   genome, chromosome, lengths, sizes
Package Dependencies:              
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-chromsizes-ggd-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-chromsizes-ggd-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-chromsizes-ggd-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-chromsizes-ggd-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.