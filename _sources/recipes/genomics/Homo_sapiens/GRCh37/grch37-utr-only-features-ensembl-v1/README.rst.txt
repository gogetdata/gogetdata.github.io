.. _`grch37-utr-only-features-ensembl-v1`:

grch37-utr-only-features-ensembl-v1
===================================

|downloads|

UTR only features from Ensembl gene sets. All other features have been removed. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.) UTRs have been designated as 5&#39; UTRs or 3&#39; UTRs based on the coding region and strand of the associated gene .Features include: five_prime_utr, three_prime_utr. Features are in GTF format.

================================== ====================================
GGD Package                        grch37-utr-only-features-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-75_2-6-14
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch37-utr-only-features-ensembl-v1.gtf.gz, grch37-utr-only-features-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File grch37-utr-only-features-ensembl-v1.gtf.gz: **3.97M**, grch37-utr-only-features-ensembl-v1.gtf.gz.tbi: **393.07K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, UTR-Only-Features, Five-Prime-UTR, Three-Prime-UTR
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-utr-only-features-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-utr-only-features-ensembl-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-utr-only-features-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-utr-only-features-ensembl-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.