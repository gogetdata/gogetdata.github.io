.. _`grch38-transcript-sequences-chr-regions-gencode-v1`:

grch38-transcript-sequences-chr-regions-gencode-v1
==================================================

|downloads|

Transcript sequences. Nucleotide sequences of all transcripts on the reference chromosomes

================================== ====================================
GGD Package                        grch38-transcript-sequences-chr-regions-gencode-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      GENCODE
Data Version                       release-34
Genomic File Type                  fa
Data file coordinate basing        NA
Package's Data Files               grch38-transcript-sequences-chr-regions-gencode-v1.fa.gz, grch38-transcript-sequences-chr-regions-gencode-v1.fa.gz.fai, grch38-transcript-sequences-chr-regions-gencode-v1.fa.gz.gzi
Approximate Size of Each Data File grch38-transcript-sequences-chr-regions-gencode-v1.fa.gz: **82.90M**, grch38-transcript-sequences-chr-regions-gencode-v1.fa.gz.fai: **31.16M**, grch38-transcript-sequences-chr-regions-gencode-v1.fa.gz.gzi: **96.46K**
Package Keywords                   gencode, fasta, transcript, transcripts
Package Dependencies:              htslib, samtools, samtools>=1.10, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-transcript-sequences-chr-regions-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-transcript-sequences-chr-regions-gencode-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-transcript-sequences-chr-regions-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-transcript-sequences-chr-regions-gencode-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.