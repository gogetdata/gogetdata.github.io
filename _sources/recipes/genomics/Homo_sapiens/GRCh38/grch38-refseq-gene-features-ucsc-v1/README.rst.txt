.. _`grch38-refseq-gene-features-ucsc-v1`:

grch38-refseq-gene-features-ucsc-v1
===================================

|downloads|

The UCSC RefSeq gene track converted into GTF format containing known human protein-coding and non-protein-coding genes from RefSeq. (RefSeq: NCBI RNA reference sequence collection). Remapped from UCSC hg38 to Ensembl GRCh38

================================== ====================================
GGD Package                        grch38-refseq-gene-features-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       01-Mar-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch38-refseq-gene-features-ucsc-v1.gtf.gz, grch38-refseq-gene-features-ucsc-v1.gtf.gz.tbi
Approximate Size of Each Data File grch38-refseq-gene-features-ucsc-v1.gtf.gz: **15.52M**, grch38-refseq-gene-features-ucsc-v1.gtf.gz.tbi: **314.88K**
Package Keywords                   RefSeq, GTF, protein-coding, non-protein-coding, refGene, UCSC-Refseq, Gene-Features
Package Dependencies:              grch38-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-refseq-gene-features-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-refseq-gene-features-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-refseq-gene-features-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-refseq-gene-features-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.