.. _`hg38-microsatellites-ucsc-v1`:

hg38-microsatellites-ucsc-v1
============================

|downloads|

Microsatellites from UCSC. Region which tend to be highly polymorphic and with at least 15 di- or tri-nucletodie repeats

================================== ====================================
GGD Package                        hg38-microsatellites-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       23-Aug-2015
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg38-microsatellites-ucsc-v1.bed.gz, hg38-microsatellites-ucsc-v1.bed.gz.tbi
Approximate Size of Each Data File hg38-microsatellites-ucsc-v1.bed.gz: **410.67K**, hg38-microsatellites-ucsc-v1.bed.gz.tbi: **306.17K**
Package Keywords                   microsatellites, microsats, STR, STRs, short-tandem-repeat, repeats, repeat-regions
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-microsatellites-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-microsatellites-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-microsatellites-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-microsatellites-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.