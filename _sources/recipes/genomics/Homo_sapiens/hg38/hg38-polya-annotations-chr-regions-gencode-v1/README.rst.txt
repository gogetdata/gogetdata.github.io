.. _`hg38-polya-annotations-chr-regions-gencode-v1`:

hg38-polya-annotations-chr-regions-gencode-v1
=============================================

|downloads|

PolyA feature annotation. It contains the polyA features (polyA_signal, polyA_site, pseudo_polyA) manually annotated by HAVANA on the reference chromosomes. This dataset does not form part of the main annotation file

================================== ====================================
GGD Package                        hg38-polya-annotations-chr-regions-gencode-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      GENCODE
Data Version                       release-34
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-polya-annotations-chr-regions-gencode-v1.gtf.gz, hg38-polya-annotations-chr-regions-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-polya-annotations-chr-regions-gencode-v1.gtf.gz: **2.02M**, hg38-polya-annotations-chr-regions-gencode-v1.gtf.gz.tbi: **305.09K**
Package Keywords                   gencode, polya, polyadenylation, annotation, gtf
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-polya-annotations-chr-regions-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics hg38-polya-annotations-chr-regions-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-polya-annotations-chr-regions-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-polya-annotations-chr-regions-gencode-v1