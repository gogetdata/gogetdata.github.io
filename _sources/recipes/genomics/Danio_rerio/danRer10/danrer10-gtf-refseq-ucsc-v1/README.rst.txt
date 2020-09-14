.. _`danrer10-gtf-refseq-ucsc-v1`:

danrer10-gtf-refseq-ucsc-v1
===========================

|downloads|

The UCSC RefSeq gene track converted into GTF format containing known zebrafish protein-coding and non-protein-coding genes from RefSeq. (RefSeq: NCBI RNA reference sequence collection) (UCSC GTF format info: https://genome.ucsc.edu/FAQ/FAQformat.html#format3)

================================== ====================================
GGD Package                        danrer10-gtf-refseq-ucsc-v1 
Species                            Danio_rerio
Genome Build                       danRer10
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      yliu 
Data Provider                      NA
Data Version                       21-May-2019
Genomic File Type                  NA
Data file coordinate basing        NA
Package's Data Files               NA
Approximate Size of Each Data File NA
Package Keywords                   GTF, RefSeq, protein-coding, non-protein-coding, refGene, UCSC
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Danio_rerio/danRer10/danrer10-gtf-refseq-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *False*. This package has not been set up to use the ``--prefix`` flag when running ggd install. Once installed, this package will work with other ggd tools that use ``--prefix`` flag.

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics danrer10-gtf-refseq-ucsc-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/danrer10-gtf-refseq-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/danrer10-gtf-refseq-ucsc-v1