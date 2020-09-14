.. _`grch37-gene-only-features-ensembl-v1`:

grch37-gene-only-features-ensembl-v1
====================================

|downloads|

Gene features only from Ensembl gene sets. All other features have been removed. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.). Features include: gene. Features are in GTF format.

================================== ====================================
GGD Package                        grch37-gene-only-features-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-75_2-6-14
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch37-gene-only-features-ensembl-v1.gtf.gz, grch37-gene-only-features-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File grch37-gene-only-features-ensembl-v1.gtf.gz: **1.34M**, grch37-gene-only-features-ensembl-v1.gtf.gz.tbi: **199.47K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, Gene-Only-Features
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-gene-only-features-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-gene-only-features-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-gene-only-features-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-gene-only-features-ensembl-v1