.. _`grch38-canonical-isoforms-ucsc-v1`:

grch38-canonical-isoforms-ucsc-v1
=================================

|downloads|

The Canonical Isofrom for each gene (or cluster) from UCSC. The APPRIS principal transcripts are used to define the canonical transcripts. If APPRIS filtering results in no transcripts, the longest isofrom is selected. Remapped from UCSC hg38 to Ensembl GRCh38

================================== ====================================
GGD Package                        grch38-canonical-isoforms-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       13-Oct-2019
Genomic File Type                  bed
Data file coordinate basing        0-based-exclusive
Package's Data Files               grch38-canonical-isoforms-ucsc-v1.bed.gz, grch38-canonical-isoforms-ucsc-v1.bed.gz.tbi
Approximate Size of Each Data File grch38-canonical-isoforms-ucsc-v1.bed.gz: **1.53M**, grch38-canonical-isoforms-ucsc-v1.bed.gz.tbi: **199.98K**
Package Keywords                   Canonical, Isofrom, Canonical-Isoform, KnownCanonical, APPRIS, APPRIS-Principal-Transcript, Canonical-Transcript, Transcript
Package Dependencies:              grch38-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, hg38-known-genes-ucsc-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-canonical-isoforms-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-canonical-isoforms-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-canonical-isoforms-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-canonical-isoforms-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.