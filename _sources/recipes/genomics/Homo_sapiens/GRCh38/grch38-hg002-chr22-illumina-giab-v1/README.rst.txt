.. _`grch38-hg002-chr22-illumina-giab-v1`:

grch38-hg002-chr22-illumina-giab-v1
===================================

|downloads|

Illumina paired-end sequencing alignments from HG002, downloaded from GIAB, and subset to 30X for chr22. Usable as an example dataset

================================== ====================================
GGD Package                        grch38-hg002-chr22-illumina-giab-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      GIAB
Data Version                       7_25_15
Genomic File Type                  bam
Data file coordinate basing        NA
Package's Data Files               grch38-hg002-chr22-illumina-giab-v1.chr22.bam, grch38-hg002-chr22-illumina-giab-v1.chr22.bam.bai
Approximate Size of Each Data File NA
Package Keywords                   giab, hg002, ashkenazi, trio, illumina, chr22, examples
Package Dependencies:              samtools
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-hg002-chr22-illumina-giab-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-hg002-chr22-illumina-giab-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-hg002-chr22-illumina-giab-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-hg002-chr22-illumina-giab-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.