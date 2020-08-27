.. _`grch38-gene-features-with-introns-ensembl-v1`:

grch38-gene-features-with-introns-ensembl-v1
============================================

|downloads|

Gene features, including all annotated transcripts, that make up the Ensembl gene sets. Intron features for each transcripts have been added to the annotation set. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.). Features include: CDS, Selenocysteine, UTR, exon, gene, intron, start_codon, stop_codon, and  transcript. Features are in GTF format

================================== ====================================
GGD Package                        grch38-gene-features-with-introns-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-100_3-7-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch38-gene-features-with-introns-ensembl-v1.gtf.gz, grch38-gene-features-with-introns-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File grch38-gene-features-with-introns-ensembl-v1.gtf.gz: **72.14M**, grch38-gene-features-with-introns-ensembl-v1.gtf.gz.tbi: **260.34K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, Intron-Features, Introns
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-gene-features-with-introns-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics grch38-gene-features-with-introns-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-gene-features-with-introns-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-gene-features-with-introns-ensembl-v1