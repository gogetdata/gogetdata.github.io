.. _`hg38-autosomal-dominant-genes-berg-blekhman-v1`:

hg38-autosomal-dominant-genes-berg-blekhman-v1
==============================================

|downloads|

CDS region genomic coordinates, along with the compliment coordinates, for combined set of OMIM disease genes deemed to follow autosomal dominant inheritance. (Assembled by Macarthur Lab). Gene sets from:  Berg et al, 2013:  (https://www.ncbi.nlm.nih.gov/pubmed/22995991). Blekham et al, 2008: (https://www.ncbi.nlm.nih.gov/pubmed/18571414)

================================== ====================================
GGD Package                        hg38-autosomal-dominant-genes-berg-blekhman-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      berg-blekhman
Data Version                       1-15-2013_6-24-2008
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg38-autosomal-dominant-genes-berg-blekhman-v1.bed.gz, hg38-autosomal-dominant-genes-berg-blekhman-v1.bed.gz.tbi, hg38-autosomal-dominant-genes-berg-blekhman-v1.compliment.bed.gz, hg38-autosomal-dominant-genes-berg-blekhman-v1.compliment.bed.gz.tbi
Approximate Size of Each Data File hg38-autosomal-dominant-genes-berg-blekhman-v1.bed.gz: **147.82K**, hg38-autosomal-dominant-genes-berg-blekhman-v1.bed.gz.tbi: **29.25K**, hg38-autosomal-dominant-genes-berg-blekhman-v1.compliment.bed.gz: **90.17K**, hg38-autosomal-dominant-genes-berg-blekhman-v1.compliment.bed.gz.tbi: **26.30K**
Package Keywords                   genes, autosomal-dominant, disease, Berg_et_al, Blekhman_et_al, AD, OMIM, gene_coordinates, CDS-regions
Package Dependencies:              bedtools, grch38-gene-features-ensembl-v1, gsort, hg38-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-autosomal-dominant-genes-berg-blekhman-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-autosomal-dominant-genes-berg-blekhman-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-autosomal-dominant-genes-berg-blekhman-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-autosomal-dominant-genes-berg-blekhman-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.