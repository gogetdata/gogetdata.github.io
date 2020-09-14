.. _`grch38-cancer-genes-futreal-v1`:

grch38-cancer-genes-futreal-v1
==============================

|downloads|

CDS region genomic coordinates, along with complement coordinates, for a manually curated set of cancer genes from Futreal et al. https://www.nature.com/articles/nrc1299. Gene symbols manually extracted from the supplemental PDF table here: https://media.nature.com/original/nature-assets/nrc/journal/v4/n3/extref/nrc1299-S1.pdf. Gene symbols manually translated to HGNC nomeclature.

================================== ====================================
GGD Package                        grch38-cancer-genes-futreal-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Futreal
Data Version                       01-March-2004
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch38-cancer-genes-futreal-v1.bed.gz, grch38-cancer-genes-futreal-v1.bed.gz.tbi, grch38-cancer-genes-futreal-v1.compliment.bed.gz, grch38-cancer-genes-futreal-v1.compliment.bed.gz.tbi
Approximate Size of Each Data File grch38-cancer-genes-futreal-v1.bed.gz: **49.01K**, grch38-cancer-genes-futreal-v1.bed.gz.tbi: **13.70K**, grch38-cancer-genes-futreal-v1.compliment.bed.gz: **31.01K**, grch38-cancer-genes-futreal-v1.compliment.bed.gz.tbi: **19.96K**
Package Keywords                   Cancer, cancer-genes, genes, Futreal, gene-set
Package Dependencies:              bedtools, grch38-gene-features-ensembl-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-cancer-genes-futreal-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-cancer-genes-futreal-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-cancer-genes-futreal-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-cancer-genes-futreal-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.