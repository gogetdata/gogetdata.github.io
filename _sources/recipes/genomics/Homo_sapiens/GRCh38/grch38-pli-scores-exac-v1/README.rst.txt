.. _`grch38-pli-scores-exac-v1`:

grch38-pli-scores-exac-v1
=========================

|downloads|

The probability of being loss-of-function intolerant (pLI) by gene scores from ExAC. See paper at: https://www.nature.com/articles/nature19057. Pseudo-liftover: Updated coordinates based on transcript ids that map between GRCh37 and GRCh38. If unable to map transcript id, the gene symbol is mapped between GRCh37 and GRCh38. If neither the transcript id or gene symbol map between the two builds the record is removed.

================================== ====================================
GGD Package                        grch38-pli-scores-exac-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      ExAC
Data Version                       Aug-31-2017
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch38-pli-scores-exac-v1.bed.gz, grch38-pli-scores-exac-v1.bed.gz.tbi
Approximate Size of Each Data File grch38-pli-scores-exac-v1.bed.gz: **532.16K**, grch38-pli-scores-exac-v1.bed.gz.tbi: **64.42K**
Package Keywords                   pLI, Probability-of-being-loss-of-function-intolerant, Constraint, LoF-Intolerance, ExAC, gene-constraint
Package Dependencies:              grch38-gene-features-ensembl-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-pli-scores-exac-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-pli-scores-exac-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-pli-scores-exac-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-pli-scores-exac-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.