.. _`hg19-intron-features-gencode-v1`:

hg19-intron-features-gencode-v1
===============================

|downloads|

Intron features created from the comprehensive set of gene anntotations created on GRCh38 and mapped to GRCh37 by GENCODE (v34lift37). Intron features for each transcripts have been added to the annotation set. ll other features are removed. Some annotations were obtained from GENCODE v19 when mapping failed. Scaffoldings, assenbly patches, and alternative loci are NOT included. Features include: intron. Remapped from Ensembl GRCh37 to UCSC hg19

================================== ====================================
GGD Package                        hg19-intron-features-gencode-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GENCODE
Data Version                       release-34_03-24-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg19-intron-features-gencode-v1.gtf.gz, hg19-intron-features-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File hg19-intron-features-gencode-v1.gtf.gz: **10.65M**, hg19-intron-features-gencode-v1.gtf.gz.tbi: **249.39K**
Package Keywords                   GTF, GENCODE-Gene-Sets, Annotated-Transcripts, Intron-Features, Introns
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-intron-features-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-intron-features-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-intron-features-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-intron-features-gencode-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.