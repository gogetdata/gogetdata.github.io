.. _`hg38-coding-exons-ensembl-v1`:

hg38-coding-exons-ensembl-v1
============================

|downloads|

Exon Coding Features. Exons that overlap coding regions in protein coding genes. Features are from Ensembl gene sets. All other features, including non-coding exon features and non-protein coding exon features, have been removed. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.). Features include: exon (exons that overlap coding regions in protein coding genes). Features are in GTF format. Remapped from Ensembl GRCh38 to UCSC hg38

================================== ====================================
GGD Package                        hg38-coding-exons-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-100_3-7-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-coding-exons-ensembl-v1.gtf.gz, hg38-coding-exons-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-coding-exons-ensembl-v1.gtf.gz: **16.56M**, hg38-coding-exons-ensembl-v1.gtf.gz.tbi: **472.11K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, Protein-Coding-Exon-Features, Coding-Exon, Protein-Coding-Exons
Package Dependencies:              gsort, hg38-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-coding-exons-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-coding-exons-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-coding-exons-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-coding-exons-ensembl-v1