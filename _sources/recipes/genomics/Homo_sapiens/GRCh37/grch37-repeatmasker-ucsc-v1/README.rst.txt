.. _`grch37-repeatmasker-ucsc-v1`:

grch37-repeatmasker-ucsc-v1
===========================

|downloads|

RepeatMasker track from UCSC in bed format. Interspersed repeats and low complexity sequences identified using the RepeatMasker program. Scaffoldings missing from the GGD hg19.genome file are removed. Remapped from UCSC hg19 to Ensembl GRCh37

================================== ====================================
GGD Package                        grch37-repeatmasker-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       22-Mar-2020
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch37-repeatmasker-ucsc-v1.bed.gz, grch37-repeatmasker-ucsc-v1.bed.gz.tbi
Approximate Size of Each Data File grch37-repeatmasker-ucsc-v1.bed.gz: **113.57M**, grch37-repeatmasker-ucsc-v1.bed.gz.tbi: **525.84K**
Package Keywords                   rmsk, region, low-complexity-repeats, SINE, ALUs, LINE, LTR, DNA-repeat-elements, simple-repeats, RNA-repeats
Package Dependencies:              grch37-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-repeatmasker-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-repeatmasker-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-repeatmasker-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-repeatmasker-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.