.. _`hg38-cds-only-features-ensembl-v1`:

hg38-cds-only-features-ensembl-v1
=================================

|downloads|

CDS only features from Ensembl gene sets. All other features have been removed. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.). Features include: CDS. Features are in GTF format. Remapped from Ensembl GRCh38 to UCSC hg38

================================== ====================================
GGD Package                        hg38-cds-only-features-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-100_3-7-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-cds-only-features-ensembl-v1.gtf.gz, hg38-cds-only-features-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-cds-only-features-ensembl-v1.gtf.gz: **14.24M**, hg38-cds-only-features-ensembl-v1.gtf.gz.tbi: **512.61K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, CDS-Only-Features
Package Dependencies:              gsort, hg38-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-cds-only-features-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-cds-only-features-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-cds-only-features-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-cds-only-features-ensembl-v1