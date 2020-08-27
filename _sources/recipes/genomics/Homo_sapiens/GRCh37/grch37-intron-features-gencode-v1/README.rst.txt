.. _`grch37-intron-features-gencode-v1`:

grch37-intron-features-gencode-v1
=================================

|downloads|

Intron features created from the  comprehensive set of gene anntotations created on GRCh38 and mapped to GRCh37 by GENCODE (v34lift37). Intron features for each transcripts have been added to the annotation set. All other features are removed. Some annotations were obtained from GENCODE v19 when mapping failed. Scaffoldings, assenbly patches, and alternative loci are NOT included. Features include: intron.

================================== ====================================
GGD Package                        grch37-intron-features-gencode-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GENCODE
Data Version                       release-34_03-24-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch37-intron-features-gencode-v1.gtf.gz, grch37-intron-features-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File grch37-intron-features-gencode-v1.gtf.gz: **10.62M**, grch37-intron-features-gencode-v1.gtf.gz.tbi: **249.10K**
Package Keywords                   GTF, GENCODE-Gene-Sets, Annotated-Transcripts, Intron-Features, Introns
Package Dependencies:              grch37-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-intron-features-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics grch37-intron-features-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-intron-features-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-intron-features-gencode-v1