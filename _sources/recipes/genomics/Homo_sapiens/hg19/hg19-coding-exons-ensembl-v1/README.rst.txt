.. _`hg19-coding-exons-ensembl-v1`:

hg19-coding-exons-ensembl-v1
============================

|downloads|

Exon Coding Features. Exons that overlap coding regions in protein coding genes. Features are from Ensembl gene sets. All other features, including non-coding exon features and non-protein coding exon features, have been removed. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.) Features include: exon (exons that overlap coding regions in protein coding genes). Features are in GTF format. Remapped from Ensembl GRCh37 to UCSC hg19

================================== ====================================
GGD Package                        hg19-coding-exons-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-75_2-6-14
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg19-coding-exons-ensembl-v1.gtf.gz, hg19-coding-exons-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File hg19-coding-exons-ensembl-v1.gtf.gz: **12.22M**, hg19-coding-exons-ensembl-v1.gtf.gz.tbi: **465.12K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, Protein-Coding-Exon-Features, Coding-Exon, Protein-Coding-Exons
Package Dependencies:              gsort, hg19-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-coding-exons-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-coding-exons-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-coding-exons-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-coding-exons-ensembl-v1