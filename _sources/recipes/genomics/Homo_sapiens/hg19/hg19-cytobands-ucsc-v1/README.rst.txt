.. _`hg19-cytobands-ucsc-v1`:

hg19-cytobands-ucsc-v1
======================

|downloads|

Approximate locations of Chromosome Bands (cytoBands) located with Giemsa-stained chromosomes from UCSC

================================== ====================================
GGD Package                        hg19-cytobands-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       14-Jun-2009
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg19-cytobands-ucsc-v1.bed.gz, hg19-cytobands-ucsc-v1.bed.gz.tbi
Approximate Size of Each Data File hg19-cytobands-ucsc-v1.bed.gz: **6.50K**, hg19-cytobands-ucsc-v1.bed.gz.tbi: **7.18K**
Package Keywords                   cytobands, ideogram, staining, chromosome, bands
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-cytobands-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-cytobands-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-cytobands-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-cytobands-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.