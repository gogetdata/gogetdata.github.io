.. _`hg19-chrom-mapping-refseq2ucsc-ncbi-v1`:

hg19-chrom-mapping-refseq2ucsc-ncbi-v1
======================================

|downloads|

A tab delimited file containing scaffolding ids that maps GRCh37 RefSeq scaffoldings to hg19 UCSC scaffoldings. This is specific to patch 13 of the GRCh37 Human genome build. (1st column = RefSeq ids, 2nd column = UCSC ids)

================================== ====================================
GGD Package                        hg19-chrom-mapping-refseq2ucsc-ncbi-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NCBI
Data Version                       12-October-2016-(patch13)
Genomic File Type                  txt
Data file coordinate basing        NA
Package's Data Files               hg19-chrom-mapping-refseq2ucsc-ncbi-v1.txt
Approximate Size of Each Data File hg19-chrom-mapping-refseq2ucsc-ncbi-v1.txt: **2.63K**
Package Keywords                   Chromosome-mapping, mapping, chrommapping, RefSeq2UCSC, scaffolding-ids, txt, patch-13, GRCh37-to-hg19
Package Dependencies:              bioawk
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-chrom-mapping-refseq2ucsc-ncbi-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-chrom-mapping-refseq2ucsc-ncbi-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-chrom-mapping-refseq2ucsc-ncbi-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-chrom-mapping-refseq2ucsc-ncbi-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.