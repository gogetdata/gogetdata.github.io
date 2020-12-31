.. _`grch38-autosomal-recessive-genes-blekhman-v1`:

grch38-autosomal-recessive-genes-blekhman-v1
============================================

|downloads|

CDS region genomic coordinates, along with the compliment coordinates, for OMIM disease genes deemed  to follow autosomal recessive inheritance according to extensive manual curation by Molly Przeworski&#39;s group.(https://www.ncbi.nlm.nih.gov/pubmed/18571414).

================================== ====================================
GGD Package                        grch38-autosomal-recessive-genes-blekhman-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      blekhman
Data Version                       6-24-2008
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch38-autosomal-recessive-genes-blekhman-v1.bed.gz, grch38-autosomal-recessive-genes-blekhman-v1.bed.gz.tbi, grch38-autosomal-recessive-genes-blekhman-v1.compliment.bed.gz, grch38-autosomal-recessive-genes-blekhman-v1.compliment.bed.gz.tbi
Approximate Size of Each Data File grch38-autosomal-recessive-genes-blekhman-v1.bed.gz: **112.75K**, grch38-autosomal-recessive-genes-blekhman-v1.bed.gz.tbi: **23.68K**, grch38-autosomal-recessive-genes-blekhman-v1.compliment.bed.gz: **70.91K**, grch38-autosomal-recessive-genes-blekhman-v1.compliment.bed.gz.tbi: **24.70K**
Package Keywords                   genes, autosomal-recessive, disease, Blekhman_et_al, AR, OMIM, gene_coordinates, CDS-regions
Package Dependencies:              bedtools, grch38-gene-features-ensembl-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-autosomal-recessive-genes-blekhman-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-autosomal-recessive-genes-blekhman-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-autosomal-recessive-genes-blekhman-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-autosomal-recessive-genes-blekhman-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.