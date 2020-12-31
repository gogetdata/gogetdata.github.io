.. _`grch38-utr-only-features-gencode-v1`:

grch38-utr-only-features-gencode-v1
===================================

|downloads|

UTR only features from the comprehensive set of gene annotations including reference chromosomes, scaffoldings, assembly patches, and alternative loci. All other features have been removed. UTRs have been designated as 5&#39; UTRs or 3&#39; UTRs based on the coding region and strand of the associated gene. Data is specific to GENCODE Release 34 (Ensembl 100). Features include: five_prime_utr, three_prime_utr.

================================== ====================================
GGD Package                        grch38-utr-only-features-gencode-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GENCODE
Data Version                       release-34_03-24-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch38-utr-only-features-gencode-v1.gtf.gz, grch38-utr-only-features-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File grch38-utr-only-features-gencode-v1.gtf.gz: **10.17M**, grch38-utr-only-features-gencode-v1.gtf.gz.tbi: **438.78K**
Package Keywords                   Gene-Features, GTF, GENOCDOE-GTF, GENCODE-Gene-Sets, Annotated-Transcripts, UTR-Only-Features, Five-Prime-UTR, Three-Prime-UTR
Package Dependencies:              grch38-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-utr-only-features-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-utr-only-features-gencode-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-utr-only-features-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-utr-only-features-gencode-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.