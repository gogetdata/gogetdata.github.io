.. _`grch37-protein-coding-features-gencode-v1`:

grch37-protein-coding-features-gencode-v1
=========================================

|downloads|

Protein Coding Features based on feature&#39;s gene biotype from  the comprehensive set of gene annotations created on GRCh38 and mapped to GRCh37 by GENCODE (v34lift37). All non-protein coding features have been removed. Some annotations were obtained from GENCODE v19 when mapping failed. Scaffoldings, assenbly patches, and alternative loci are NOT included. Features include: CDS, Selenocysteine, UTR, exon, gene, start_codon, stop_codon, transcript.

================================== ====================================
GGD Package                        grch37-protein-coding-features-gencode-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GENCODE
Data Version                       release-34_03-24-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch37-protein-coding-features-gencode-v1.gtf.gz, grch37-protein-coding-features-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File grch37-protein-coding-features-gencode-v1.gtf.gz: **60.21M**, grch37-protein-coding-features-gencode-v1.gtf.gz.tbi: **244.29K**
Package Keywords                   Gene-Features, GTF, GENOCDOE-GTF, GENCODE-Gene-Sets, Annotated-Transcripts, Protein-Coding-Features
Package Dependencies:              grch37-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-protein-coding-features-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-protein-coding-features-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-protein-coding-features-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-protein-coding-features-gencode-v1