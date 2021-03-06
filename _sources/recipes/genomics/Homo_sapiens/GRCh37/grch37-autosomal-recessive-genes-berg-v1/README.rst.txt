.. _`grch37-autosomal-recessive-genes-berg-v1`:

grch37-autosomal-recessive-genes-berg-v1
========================================

|downloads|

CDS region genomic coordinates, along with the compliment coordinates, for OMIM disease genes (as of June 2011) deemed to follow autosomal recessive inheritance. (Assembled by Macarthur Lab). Berg et al, 2013:  (https://www.ncbi.nlm.nih.gov/pubmed/22995991).

================================== ====================================
GGD Package                        grch37-autosomal-recessive-genes-berg-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      berg
Data Version                       1-15-2013
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch37-autosomal-recessive-genes-berg-v1.bed.gz, grch37-autosomal-recessive-genes-berg-v1.bed.gz.tbi, grch37-autosomal-recessive-genes-berg-v1.compliment.bed.gz, grch37-autosomal-recessive-genes-berg-v1.compliment.bed.gz.tbi
Approximate Size of Each Data File grch37-autosomal-recessive-genes-berg-v1.bed.gz: **198.95K**, grch37-autosomal-recessive-genes-berg-v1.bed.gz.tbi: **43.81K**, grch37-autosomal-recessive-genes-berg-v1.compliment.bed.gz: **121.42K**, grch37-autosomal-recessive-genes-berg-v1.compliment.bed.gz.tbi: **26.61K**
Package Keywords                   genes, autosomal-recessive, disease, Berg_et_al, AR, OMIM, gene_coordinates, CDS-regions
Package Dependencies:              bedtools, grch37-gene-features-ensembl-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-autosomal-recessive-genes-berg-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-autosomal-recessive-genes-berg-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-autosomal-recessive-genes-berg-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-autosomal-recessive-genes-berg-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.