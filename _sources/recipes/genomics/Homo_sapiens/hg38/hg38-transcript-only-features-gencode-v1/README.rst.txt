.. _`hg38-transcript-only-features-gencode-v1`:

hg38-transcript-only-features-gencode-v1
========================================

|downloads|

Transcript only features from the comprehensive set of gene annotations including reference chromosomes, scaffoldings, assembly patches, and alternative loci. All other features have been removed. Data is specific to GENCODE Release 34 (Ensembl 100). Features include: transcript. Remapped from Ensembl GRCh38 to UCSC hg38.

================================== ====================================
GGD Package                        hg38-transcript-only-features-gencode-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GENCODE
Data Version                       release-34_03-24-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-transcript-only-features-gencode-v1.gtf.gz, hg38-transcript-only-features-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-transcript-only-features-gencode-v1.gtf.gz: **9.81M**, hg38-transcript-only-features-gencode-v1.gtf.gz.tbi: **226.76K**
Package Keywords                   Gene-Features, GTF, GENOCDOE-GTF, GENCODE-Gene-Sets, Annotated-Transcripts, Transcript-Only-Features
Package Dependencies:              gsort, hg38-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-transcript-only-features-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-transcript-only-features-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-transcript-only-features-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-transcript-only-features-gencode-v1