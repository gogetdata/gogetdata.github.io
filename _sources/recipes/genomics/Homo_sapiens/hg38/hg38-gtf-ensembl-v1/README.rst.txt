.. _`hg38-gtf-ensembl-v1`:

hg38-gtf-ensembl-v1
===================

|downloads|

The GRCh38 gtf file from ensembl remapped to hg38 (Any unmapped entries are removed from the file)

================================== ====================================
GGD Package                        hg38-gtf-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NA
Data Version                       release-96
Genomic File Type                  NA
Data file coordinate basing        NA
Package's Data Files               NA
Approximate Size of Each Data File NA
Package Keywords                   gtf, gtf-file, ensembl
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-gtf-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *False*. This package has not been set up to use the ``--prefix`` flag when running ggd install. Once installed, this package will work with other ggd tools that use ``--prefix`` flag.

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-gtf-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-gtf-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-gtf-ensembl-v1