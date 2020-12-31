.. _`grch38-self-chain-high-identity-ucsc-v1`:

grch38-self-chain-high-identity-ucsc-v1
=======================================

|downloads|

High identity, &gt;=90%, Self chain alignments of the human genome with an improved gap scoring system. Genomic coordinates are merged across all overlapping intervals, providing continuous high identity self chain repeat regions. Alignments point out areas of duplication within the human genome, with the exception of the pseudoautosomal regions on X and Y. From the Human Chained Self Alignemnts track on UCSC. Remapped from UCSC hg38 to Ensembl GRCh37

================================== ====================================
GGD Package                        grch38-self-chain-high-identity-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       06-Mar-2014
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch38-self-chain-high-identity-ucsc-v1.bed.gz, grch38-self-chain-high-identity-ucsc-v1.bed.gz.tbi
Approximate Size of Each Data File grch38-self-chain-high-identity-ucsc-v1.bed.gz: **61.66K**, grch38-self-chain-high-identity-ucsc-v1.bed.gz.tbi: **52.74K**
Package Keywords                   Self-Chain, Self-Alignment, Repeats, low-copy-repeats, High-Identity, >=90%-Identity
Package Dependencies:              bedtools, grch38-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-self-chain-high-identity-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-self-chain-high-identity-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-self-chain-high-identity-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-self-chain-high-identity-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.