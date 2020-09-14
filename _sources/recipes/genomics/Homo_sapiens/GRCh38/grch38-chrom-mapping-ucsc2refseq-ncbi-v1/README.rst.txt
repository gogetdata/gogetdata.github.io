.. _`grch38-chrom-mapping-ucsc2refseq-ncbi-v1`:

grch38-chrom-mapping-ucsc2refseq-ncbi-v1
========================================

|downloads|

A tab delimited file containing scaffolding ids that map hg38 UCSC to GRCh38 RefSeq scaffoldings. This is specific to patch 13 of the GRCh38 Human genome build. (1st column = UCSC ids, 2nd Column = RefSeq ids)

================================== ====================================
GGD Package                        grch38-chrom-mapping-ucsc2refseq-ncbi-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NCBI
Data Version                       14-April-2020-(patch13)
Genomic File Type                  txt
Data file coordinate basing        NA
Package's Data Files               grch38-chrom-mapping-ucsc2refseq-ncbi-v1.txt
Approximate Size of Each Data File grch38-chrom-mapping-ucsc2refseq-ncbi-v1.txt: **19.31K**
Package Keywords                   Chromosome-mapping, mapping, chrommapping, UCSC2RefSeq, scaffolding-ids, txt, patch-13
Package Dependencies:              bioawk
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-chrom-mapping-ucsc2refseq-ncbi-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-chrom-mapping-ucsc2refseq-ncbi-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-chrom-mapping-ucsc2refseq-ncbi-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-chrom-mapping-ucsc2refseq-ncbi-v1