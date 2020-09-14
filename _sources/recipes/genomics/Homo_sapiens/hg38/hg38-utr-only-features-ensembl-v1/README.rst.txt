.. _`hg38-utr-only-features-ensembl-v1`:

hg38-utr-only-features-ensembl-v1
=================================

|downloads|

UTR only features from Ensembl gene sets. All other features have been removed. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.). Features include: five_prime_utr, three_prime_utr. Features are in GTF format. Remapped from Ensembl GRCh38 to UCSC hg38

================================== ====================================
GGD Package                        hg38-utr-only-features-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-100_3-7-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-utr-only-features-ensembl-v1.gtf.gz, hg38-utr-only-features-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-utr-only-features-ensembl-v1.gtf.gz: **5.63M**, hg38-utr-only-features-ensembl-v1.gtf.gz.tbi: **403.06K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, UTR-Only-Features, Five-Prime-UTR, Three-Prime-UTR
Package Dependencies:              gsort, hg38-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-utr-only-features-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-utr-only-features-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-utr-only-features-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-utr-only-features-ensembl-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.