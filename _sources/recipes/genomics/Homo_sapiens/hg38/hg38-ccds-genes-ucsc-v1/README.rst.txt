.. _`hg38-ccds-genes-ucsc-v1`:

hg38-ccds-genes-ucsc-v1
=======================

|downloads|

Consensus Coding Seqeunce (CCDS) high confidence gene annotation from UCSC. The annotation here are  high quality manually curated protein-coding regions from the Consensus CDS project.

================================== ====================================
GGD Pacakge                        hg38-ccds-genes-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       20-Oct-2019
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg38-ccds-genes-ucsc-v1.bed.gz, hg38-ccds-genes-ucsc-v1.bed.gz.tbi
Approximate Size of Each Data File hg38-ccds-genes-ucsc-v1.bed.gz: **2.37M**, hg38-ccds-genes-ucsc-v1.bed.gz.tbi: **92.25K**
Package Keywords                   Consensus-Coding-Sequence, CCDS, high-confident, gene-annotations, protein-coding, CDS, Genes, CCDS-Project, protein-coding-genes
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-ccds-genes-ucsc-v1
================================== ====================================



Installation
------------

.. highlight: bash

With ggd insatlled and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics hg38-ccds-genes-ucsc-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-ccds-genes-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-ccds-genes-ucsc-v1