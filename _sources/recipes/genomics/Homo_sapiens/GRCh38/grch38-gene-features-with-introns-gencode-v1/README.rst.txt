.. _`grch38-gene-features-with-introns-gencode-v1`:

grch38-gene-features-with-introns-gencode-v1
============================================

|downloads|

Comprehensive set of gene anntotations including reference chromosomes, scaffoldings, assebly patches, and alternative loci. Intron features for each transcripts have been added to the annotation set. Data is specific to GENCODE Release 34 (Ensembl 100). Features include: gene, transcript, exon, intron, CDS, UTR, start_codon, stop_codon, and Selenocysteine.

================================== ====================================
GGD Package                        grch38-gene-features-with-introns-gencode-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GENCODE
Data Version                       release-34_03-24-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch38-gene-features-with-introns-gencode-v1.gtf.gz, grch38-gene-features-with-introns-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File grch38-gene-features-with-introns-gencode-v1.gtf.gz: **76.99M**, grch38-gene-features-with-introns-gencode-v1.gtf.gz.tbi: **290.27K**
Package Keywords                   Gene-Features, Gene-Annotations, All-Regions, GTF, GENOCDOE-GTF, GENCODE-Gene-Sets, Annotated-Transcripts, Intron-Features, Introns
Package Dependencies:              grch38-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-gene-features-with-introns-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-gene-features-with-introns-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-gene-features-with-introns-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-gene-features-with-introns-gencode-v1