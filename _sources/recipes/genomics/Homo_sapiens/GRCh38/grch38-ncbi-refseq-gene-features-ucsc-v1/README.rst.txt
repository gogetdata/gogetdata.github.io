.. _`grch38-ncbi-refseq-gene-features-ucsc-v1`:

grch38-ncbi-refseq-gene-features-ucsc-v1
========================================

|downloads|

Gene features for all curated and predicted annotations from the NCBI Refseq track from UCSC. (GTF). Refseq ALL. Human protein-coding and non-protein-coding genes from NCBI RNA reference seqeunce collection. Remapped from UCSC hg38 to Ensembl GRCh38

================================== ====================================
GGD Package                        grch38-ncbi-refseq-gene-features-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       10-Jan-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch38-ncbi-refseq-gene-features-ucsc-v1.gtf.gz, grch38-ncbi-refseq-gene-features-ucsc-v1.gtf.gz.tbi
Approximate Size of Each Data File grch38-ncbi-refseq-gene-features-ucsc-v1.gtf.gz: **34.53M**, grch38-ncbi-refseq-gene-features-ucsc-v1.gtf.gz.tbi: **356.51K**
Package Keywords                   GTF, gene-feature-file, NCBI-Refseq, Refseq-All
Package Dependencies:              grch38-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-ncbi-refseq-gene-features-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-ncbi-refseq-gene-features-ucsc-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-ncbi-refseq-gene-features-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-ncbi-refseq-gene-features-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.