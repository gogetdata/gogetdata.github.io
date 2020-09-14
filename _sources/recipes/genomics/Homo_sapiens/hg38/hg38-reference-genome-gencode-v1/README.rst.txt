.. _`hg38-reference-genome-gencode-v1`:

hg38-reference-genome-gencode-v1
================================

|downloads|

Genome sequence, primary assembly. Nucleotide sequence of the hg38 primary genome assembly (chromosomes and scaffolds)

================================== ====================================
GGD Package                        hg38-reference-genome-gencode-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      GENCODE
Data Version                       release-34
Genomic File Type                  fa
Data file coordinate basing        NA
Package's Data Files               hg38-reference-genome-gencode-v1.fa.gz, hg38-reference-genome-gencode-v1.fa.gz.fai, hg38-reference-genome-gencode-v1.fa.gz.gzi
Approximate Size of Each Data File hg38-reference-genome-gencode-v1.fa.gz: **894.51M**, hg38-reference-genome-gencode-v1.fa.gz.fai: **6.48K**, hg38-reference-genome-gencode-v1.fa.gz.gzi: **772.41K**
Package Keywords                   reference, primary-assembly, gencode, fasta
Package Dependencies:              htslib, samtools, samtools>=1.10, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-reference-genome-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-reference-genome-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-reference-genome-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-reference-genome-gencode-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.