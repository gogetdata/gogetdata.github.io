.. _`grch38-toplevel-reference-genome-ensembl-v1`:

grch38-toplevel-reference-genome-ensembl-v1
===========================================

|downloads|

The GRCh38 unmasked genomic DNA seqeunce reference genome from Ensembl-Release 99. Includes all sequence regions flagged as toplevel by Ensembl including chromosomes, regions not assembled into chromosomes, and N padded haplotype/patch regions. &#39;Top Level file&#39;

================================== ====================================
GGD Package                        grch38-toplevel-reference-genome-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-99_11-18-19
Genomic File Type                  fa
Data file coordinate basing        NA
Package's Data Files               grch38-toplevel-reference-genome-ensembl-v1.fa.gz, grch38-toplevel-reference-genome-ensembl-v1.fa.gz.fai, grch38-toplevel-reference-genome-ensembl-v1.fa.gz.gzi
Approximate Size of Each Data File grch38-toplevel-reference-genome-ensembl-v1.fa.gz: **1.29G**, grch38-toplevel-reference-genome-ensembl-v1.fa.gz.fai: **27.85K**, grch38-toplevel-reference-genome-ensembl-v1.fa.gz.gzi: **15.74M**
Package Keywords                   Top-Level, Release-99, ref, reference, Ensembl-ref, DNA-Seqeunce, Fasta-Seqeunce, fasta-file
Package Dependencies:              samtools, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-toplevel-reference-genome-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-toplevel-reference-genome-ensembl-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-toplevel-reference-genome-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-toplevel-reference-genome-ensembl-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.