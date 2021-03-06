.. _`hg38-haploinsufficient-genes-clingen-v1`:

hg38-haploinsufficient-genes-clingen-v1
=======================================

|downloads|

CDS region genomic coordinates, along with complement coordinates, for a set of haploinsufficient genes from ClinGen&#39;s Dosage Sensitivity Map curated by Daniel MacArthur&#39;&#39;s lab. The genes used are those that are haplosensitive and not triplosensitive, and are level 3 (the maximum level) dosage sensitive. Original work on this is part of the Cytogenomic Arrays Consortium. Paper at: &#39;https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5008023/&#39;. Any genes in patch regions or non-reference scaffoldings are not included.

================================== ====================================
GGD Package                        hg38-haploinsufficient-genes-clingen-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      ClinGen
Data Version                       01-Sept-2016
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg38-haploinsufficient-genes-clingen-v1.bed.gz, hg38-haploinsufficient-genes-clingen-v1.bed.gz.tbi, hg38-haploinsufficient-genes-clingen-v1.compliment.bed.gz, hg38-haploinsufficient-genes-clingen-v1.compliment.bed.gz.tbi
Approximate Size of Each Data File hg38-haploinsufficient-genes-clingen-v1.bed.gz: **50.07K**, hg38-haploinsufficient-genes-clingen-v1.bed.gz.tbi: **14.35K**, hg38-haploinsufficient-genes-clingen-v1.compliment.bed.gz: **32.30K**, hg38-haploinsufficient-genes-clingen-v1.compliment.bed.gz.tbi: **19.34K**
Package Keywords                   haploinsufficiency, haploinsufficient, haploinsufficient-genes, genes, Clingen, gene-set
Package Dependencies:              bedtools, grch38-gene-features-ensembl-v1, gsort, hg38-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, pyexcel, pyexcel-xls, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-haploinsufficient-genes-clingen-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-haploinsufficient-genes-clingen-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-haploinsufficient-genes-clingen-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-haploinsufficient-genes-clingen-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.