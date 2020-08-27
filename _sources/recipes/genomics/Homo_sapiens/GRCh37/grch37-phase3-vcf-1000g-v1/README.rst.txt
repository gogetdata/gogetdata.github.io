.. _`grch37-phase3-vcf-1000g-v1`:

grch37-phase3-vcf-1000g-v1
==========================

|downloads|

The phase3 1000g vcf file distrubted on 05/02/2013 in vcf format (decomposed and normalized)

================================== ====================================
GGD Package                        grch37-phase3-vcf-1000g-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NA
Data Version                       phase3 - 20130502 - 8/17/15
Genomic File Type                  NA
Data file coordinate basing        NA
Package's Data Files               NA
Approximate Size of Each Data File NA
Package Keywords                   1000g-variants, 1000g, wgs, sites, vcf-file
Package Dependencies:              grch37-sequence-1000g-v1, gsort, htslib, vt, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-phase3-vcf-1000g-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *False*. This package has not been set up to use the ``--prefix`` flag when running ggd install. Once installed, this package will work with other ggd tools that use ``--prefix`` flag.

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics grch37-phase3-vcf-1000g-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-phase3-vcf-1000g-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-phase3-vcf-1000g-v1