.. _`hg38-structural-variants-bedpe-ccdg-v1`:

hg38-structural-variants-bedpe-ccdg-v1
======================================

|downloads|

SV callset 2 from ccdg in hg38, bedpe format

================================== ====================================
GGD Package                        hg38-structural-variants-bedpe-ccdg-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      ccdg
Data Version                       2
Genomic File Type                  bedpe
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg38-structural-variants-bedpe-ccdg-v1.public.v2.sorted.bedpe.gz, hg38-structural-variants-bedpe-ccdg-v1.public.v2.sorted.bedpe.gz.tbi
Approximate Size of Each Data File hg38-structural-variants-bedpe-ccdg-v1.public.v2.sorted.bedpe.gz: **52.01M**, hg38-structural-variants-bedpe-ccdg-v1.public.v2.sorted.bedpe.gz.tbi: **1.22M**
Package Keywords                   sv, ccdg, structural-variants, sv, structural, bedpe-file, bed-file
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-structural-variants-bedpe-ccdg-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-structural-variants-bedpe-ccdg-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-structural-variants-bedpe-ccdg-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-structural-variants-bedpe-ccdg-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.