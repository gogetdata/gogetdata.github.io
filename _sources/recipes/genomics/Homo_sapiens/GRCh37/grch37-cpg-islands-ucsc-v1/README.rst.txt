.. _`grch37-cpg-islands-ucsc-v1`:

grch37-cpg-islands-ucsc-v1
==========================

|downloads|

cpg islands from UCSC in bed format. Remapped from UCSC hg19 to Ensembl GRCh37. Any scaffoldings that are not in the GRCh37.genome file or that cannot be remapped are removed

================================== ====================================
GGD Package                        grch37-cpg-islands-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       22-Mar-2020
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch37-cpg-islands-ucsc-v1.bed.gz, grch37-cpg-islands-ucsc-v1.bed.gz.tbi
Approximate Size of Each Data File grch37-cpg-islands-ucsc-v1.bed.gz: **614.42K**, grch37-cpg-islands-ucsc-v1.bed.gz.tbi: **185.26K**
Package Keywords                   CpG, region, bed-file, cpg-islands, islands
Package Dependencies:              grch37-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-cpg-islands-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-cpg-islands-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-cpg-islands-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-cpg-islands-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.