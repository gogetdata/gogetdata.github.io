.. _`hg38-protein-coding-features-ensembl-v1`:

hg38-protein-coding-features-ensembl-v1
=======================================

|downloads|

Protein Coding Features based on feature&#39;s gene biotype from Ensembl gene sets. All non-protein coding features have been removed. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.). Features include: CDS, Selenocysteine, five_prime_utr, three_prime_utr, exon, gene, start_codon, stop_codon, transcript. Features are in GTF format. Remapped from Ensembl GRCh38 to UCSC hg38

================================== ====================================
GGD Package                        hg38-protein-coding-features-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-100_3-7-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-protein-coding-features-ensembl-v1.gtf.gz, hg38-protein-coding-features-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-protein-coding-features-ensembl-v1.gtf.gz: **48.71M**, hg38-protein-coding-features-ensembl-v1.gtf.gz.tbi: **235.71K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, Protein-Coding-Features
Package Dependencies:              gsort, hg38-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-protein-coding-features-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics hg38-protein-coding-features-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-protein-coding-features-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-protein-coding-features-ensembl-v1