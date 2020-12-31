.. _`grch37-structural-variants-database-genomic-variants-ucsc-v1`:

grch37-structural-variants-database-genomic-variants-ucsc-v1
============================================================

|downloads|

Database of Genomic Variants incorporating dbVar, July 2013 and later

================================== ====================================
GGD Package                        grch37-structural-variants-database-genomic-variants-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      UCSC
Data Version                       2020-01-13
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch37-structural-variants-database-genomic-variants-ucsc-v1.bed.gz, grch37-structural-variants-database-genomic-variants-ucsc-v1.bed.gz.tbi
Approximate Size of Each Data File grch37-structural-variants-database-genomic-variants-ucsc-v1.bed.gz: **73.99M**, grch37-structural-variants-database-genomic-variants-ucsc-v1.bed.gz.tbi: **215.69K**
Package Keywords                   structural-variants, structural-variant, SVs, SV, dbVar, dbvar
Package Dependencies:              grch37-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-structural-variants-database-genomic-variants-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-structural-variants-database-genomic-variants-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-structural-variants-database-genomic-variants-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-structural-variants-database-genomic-variants-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.