.. _`grch37-hg003-pb-chr22-giab-v1`:

grch37-hg003-pb-chr22-giab-v1
=============================

|downloads|

GiaB PacBio 30x sequencing for chromosome 22 in ashkenazi sample HG003

================================== ====================================
GGD Package                        grch37-hg003-pb-chr22-giab-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      giab
Data Version                       11-18-15
Genomic File Type                  fastq
Data file coordinate basing        NA
Package's Data Files               grch37-hg003-pb-chr22-giab-v1.fastq.gz, grch37-hg003-pb-chr22-giab-v1.fastq.gz.fai, grch37-hg003-pb-chr22-giab-v1.fastq.gz.gzi
Approximate Size of Each Data File NA
Package Keywords                   ashkenazi, hg003, pacbio, pb, giab, chr22, trio
Package Dependencies:              htslib, samtools, wget, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-hg003-pb-chr22-giab-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-hg003-pb-chr22-giab-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-hg003-pb-chr22-giab-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-hg003-pb-chr22-giab-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.