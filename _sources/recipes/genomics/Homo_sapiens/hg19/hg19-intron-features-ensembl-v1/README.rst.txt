.. _`hg19-intron-features-ensembl-v1`:

hg19-intron-features-ensembl-v1
===============================

|downloads|

Intron features created from the Ensembl gene features, including all annotated transcripts, that make up the Ensembl gene sets. Intron features for each transcripts have been added to the annotation set. All other features are removed. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.). Features include: intron. Features are in GTF format. Remapped from Ensembl GRCh37 to UCSC hg19

================================== ====================================
GGD Package                        hg19-intron-features-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-75_2-6-14
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg19-intron-features-ensembl-v1.gtf.gz, hg19-intron-features-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File hg19-intron-features-ensembl-v1.gtf.gz: **8.90M**, hg19-intron-features-ensembl-v1.gtf.gz.tbi: **241.37K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Intron-Features, Introns, Intron-Features-Only
Package Dependencies:              gsort, hg19-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-intron-features-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics hg19-intron-features-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-intron-features-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-intron-features-ensembl-v1