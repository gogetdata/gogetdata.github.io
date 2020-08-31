.. _`hg19-utr-only-features-gencode-v1`:

hg19-utr-only-features-gencode-v1
=================================

|downloads|

UTR only features from the comprehensive set of gene annotations created on GRCh38 and mapped to GRCh37 by GENCODE (v34lift37). All other features have been removed. UTRs have been designated as 5&#39; UTRs or 3&#39; UTRs based on the coding region and strand of the associated gene. Features include: five_prime_utr, three_prime_utr. Some annotations were obtained from GENCODE v19 when mapping failed. Scaffoldings, assembly patches, and alternative loci are NOT included. Remapped from Ensembl GRCh37 to UCSC hg19

================================== ====================================
GGD Package                        hg19-utr-only-features-gencode-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GENCODE
Data Version                       release-34_03-24-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg19-utr-only-features-gencode-v1.gtf.gz, hg19-utr-only-features-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File hg19-utr-only-features-gencode-v1.gtf.gz: **11.98M**, hg19-utr-only-features-gencode-v1.gtf.gz.tbi: **408.72K**
Package Keywords                   Gene-Features, GTF, GENOCDOE-GTF, GENCODE-Gene-Sets, Annotated-Transcripts, UTR-Only-Features, Five-Prime-UTR, Three-Prime-UTR
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-utr-only-features-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics hg19-utr-only-features-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-utr-only-features-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-utr-only-features-gencode-v1