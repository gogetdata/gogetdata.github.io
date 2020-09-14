.. _`grch37-coding-exons-ensembl-v1`:

grch37-coding-exons-ensembl-v1
==============================

|downloads|

Exon Coding Features. Exons that overlap coding regions in protein coding genes. Features are from Ensembl gene sets. All other features, including non-coding exon features and non-protein coding exon features, have been removed. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.). Features include: exon (exons that overlap coding regions in protein coding genes). Features are in GTF format.

================================== ====================================
GGD Package                        grch37-coding-exons-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-75_2-6-14
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch37-coding-exons-ensembl-v1.gtf.gz, grch37-coding-exons-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File grch37-coding-exons-ensembl-v1.gtf.gz: **12.20M**, grch37-coding-exons-ensembl-v1.gtf.gz.tbi: **465.25K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, Protein-Coding-Exon-Features, Coding-Exon, Protein-Coding-Exons
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-coding-exons-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-coding-exons-ensembl-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-coding-exons-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-coding-exons-ensembl-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.