.. _`hg19-1000g-omni-snps-broad-v1`:

hg19-1000g-omni-snps-broad-v1
=============================

|downloads|

The 1000G omni snps vcf file hosted on the broad&#39;s ftp site

================================== ====================================
GGD Package                        hg19-1000g-omni-snps-broad-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NA
Data Version                       2.5 - 12/7/13
Genomic File Type                  NA
Data file coordinate basing        NA
Package's Data Files               NA
Approximate Size of Each Data File NA
Package Keywords                   omni, snps, 1000G, broad-institute, vcf-fil
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-1000g-omni-snps-broad-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *False*. This package has not been set up to use the ``--prefix`` flag when running ggd install. Once installed, this package will work with other ggd tools that use ``--prefix`` flag.

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-1000g-omni-snps-broad-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-1000g-omni-snps-broad-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-1000g-omni-snps-broad-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.