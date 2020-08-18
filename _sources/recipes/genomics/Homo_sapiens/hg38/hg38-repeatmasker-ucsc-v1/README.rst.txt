.. _`hg38-repeatmasker-ucsc-v1`:

hg38-repeatmasker-ucsc-v1
=========================

|downloads|

RepeatMasker track from UCSC in bed format. Interspersed repeats and low complexity sequences identified using the RepeatMasker program.

================================== ====================================
GGD Pacakge                        hg38-repeatmasker-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       11-Mar-2019
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg38-repeatmasker-ucsc-v1.bed.gz, hg38-repeatmasker-ucsc-v1.bed.gz.tbi
Approximate Size of Each Data File hg38-repeatmasker-ucsc-v1.bed.gz: **124.47M**, hg38-repeatmasker-ucsc-v1.bed.gz.tbi: **561.26K**
Package Keywords                   rmsk, region, low-complexity-repeats, SINE, ALUs, LINE, LTR, DNA-repeat-elements, simple-repeats, RNA-repeats
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-repeatmasker-ucsc-v1
================================== ====================================



Installation
------------

.. highlight: bash

With ggd insatlled and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics hg38-repeatmasker-ucsc-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-repeatmasker-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-repeatmasker-ucsc-v1