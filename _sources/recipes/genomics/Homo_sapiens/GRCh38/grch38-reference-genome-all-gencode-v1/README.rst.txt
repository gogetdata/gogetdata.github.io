.. _`grch38-reference-genome-all-gencode-v1`:

grch38-reference-genome-all-gencode-v1
======================================

|downloads|

Genome sequence. Nucleotide sequence of the GRCh38.p13 genome assembly version on all regions, including reference chromosomes, scaffolds, assembly patches and haplotypes

================================== ====================================
GGD Package                        grch38-reference-genome-all-gencode-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      GENCODE
Data Version                       release-34,patch-13
Genomic File Type                  fa
Data file coordinate basing        NA
Package's Data Files               grch38-reference-genome-all-gencode-v1.fa.gz, grch38-reference-genome-all-gencode-v1.fa.gz.fai, grch38-reference-genome-all-gencode-v1.fa.gz.gzi
Approximate Size of Each Data File grch38-reference-genome-all-gencode-v1.fa.gz: **942.24M**, grch38-reference-genome-all-gencode-v1.fa.gz.fai: **21.95K**, grch38-reference-genome-all-gencode-v1.fa.gz.gzi: **814.12K**
Package Keywords                   reference, all-assembly, gencode, fasta
Package Dependencies:              htslib, samtools, samtools>=1.10, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-reference-genome-all-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-reference-genome-all-gencode-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-reference-genome-all-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-reference-genome-all-gencode-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.