.. _`hg19-gtf-refseq-ucsc-v1`:

hg19-gtf-refseq-ucsc-v1
=======================

|downloads|

The UCSC RefSeq gene track converted into GTF format containing known human protein-coding and non-protein-coding genes from RefSeq. (RefSeq: NCBI RNA reference sequence collection) (UCSC GTF format info: https://genome.ucsc.edu/FAQ/FAQformat.html#format3)

================================== ====================================
GGD Package                        hg19-gtf-refseq-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NA
Data Version                       31-Mar-2019
Genomic File Type                  NA
Data file coordinate basing        NA
Package's Data Files               NA
Approximate Size of Each Data File NA
Package Keywords                   GTF, ReFSeq, potein-coding, non-protein-coding, refGene, UCSC
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-gtf-refseq-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *False*. This package has not been set up to use the ``--prefix`` flag when running ggd install. Once installed, this package will work with other ggd tools that use ``--prefix`` flag.

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-gtf-refseq-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-gtf-refseq-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-gtf-refseq-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.