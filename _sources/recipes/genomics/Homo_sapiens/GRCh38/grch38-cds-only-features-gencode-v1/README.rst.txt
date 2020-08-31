.. _`grch38-cds-only-features-gencode-v1`:

grch38-cds-only-features-gencode-v1
===================================

|downloads|

CDS only features from the comprehensive set of gene annotations including reference chromosomes, scaffoldings, assembly patches, and alternative loci. All other features have been removed. Data is specific to GENCODE Release 34 (Ensembl 100). Features include: CDS.

================================== ====================================
GGD Package                        grch38-cds-only-features-gencode-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GENCODE
Data Version                       release-34_03-24-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch38-cds-only-features-gencode-v1.gtf.gz, grch38-cds-only-features-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File grch38-cds-only-features-gencode-v1.gtf.gz: **18.49M**, grch38-cds-only-features-gencode-v1.gtf.gz.tbi: **549.66K**
Package Keywords                   Gene-Features, GTF, GENOCDOE-GTF, GENCODE-Gene-Sets, Annotated-Transcripts, CDS-Only-Features
Package Dependencies:              grch38-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-cds-only-features-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics grch38-cds-only-features-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-cds-only-features-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-cds-only-features-gencode-v1