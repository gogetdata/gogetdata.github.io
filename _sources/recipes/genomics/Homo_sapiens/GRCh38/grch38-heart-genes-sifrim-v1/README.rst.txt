.. _`grch38-heart-genes-sifrim-v1`:

grch38-heart-genes-sifrim-v1
============================

|downloads|

CDS region genomic coordinates, along with complement coordinates, for a manually curated set of congenital heart disease (CHD) genes from Sifrim et al. (www.nature.com/articles/ng.3627). Used Supplemental Table 20 here: https://media.nature.com/original/nature-assets/ng/journal/v48/n9/extref/ng.3627-S13.xlsx

================================== ====================================
GGD Package                        grch38-heart-genes-sifrim-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Sifrim
Data Version                       01-Aug-2016
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch38-heart-genes-sifrim-v1.bed.gz, grch38-heart-genes-sifrim-v1.bed.gz.tbi, grch38-heart-genes-sifrim-v1.complement.bed.gz, grch38-heart-genes-sifrim-v1.complement.bed.gz.tbi
Approximate Size of Each Data File grch38-heart-genes-sifrim-v1.bed.gz: **42.23K**, grch38-heart-genes-sifrim-v1.bed.gz.tbi: **12.05K**, grch38-heart-genes-sifrim-v1.complement.bed.gz: **28.85K**, grch38-heart-genes-sifrim-v1.complement.bed.gz.tbi: **19.29K**
Package Keywords                   heart, heart-disease, heart-genes, genes, sifrim, gene-set
Package Dependencies:              bedtools, grch38-gene-features-ensembl-v1, gsort, htslib, pyexcel, pyexcel-xls, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-heart-genes-sifrim-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-heart-genes-sifrim-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-heart-genes-sifrim-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-heart-genes-sifrim-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.