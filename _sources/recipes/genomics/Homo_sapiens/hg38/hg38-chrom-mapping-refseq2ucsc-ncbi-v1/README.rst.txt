.. _`hg38-chrom-mapping-refseq2ucsc-ncbi-v1`:

hg38-chrom-mapping-refseq2ucsc-ncbi-v1
======================================

|downloads|

A tab delimited file containing scaffolding ids that map GRCh38 RefSeq to hg38 UCSC scaffoldings. This is specific to patch 13 of the GRCh38 Human genome build. (1st Column = RefSeq ids, 2nd Column = UCSC ids)

================================== ====================================
GGD Package                        hg38-chrom-mapping-refseq2ucsc-ncbi-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NCBI
Data Version                       14-April-2020-(patch13)
Genomic File Type                  txt
Data file coordinate basing        NA
Package's Data Files               hg38-chrom-mapping-refseq2ucsc-ncbi-v1.txt
Approximate Size of Each Data File hg38-chrom-mapping-refseq2ucsc-ncbi-v1.txt: **19.51K**
Package Keywords                   Chromosome-mapping, mapping, chrommapping, RefSeq2UCSC, scaffolding-ids, txt, patch-13
Package Dependencies:              bioawk
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-chrom-mapping-refseq2ucsc-ncbi-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-chrom-mapping-refseq2ucsc-ncbi-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-chrom-mapping-refseq2ucsc-ncbi-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-chrom-mapping-refseq2ucsc-ncbi-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.