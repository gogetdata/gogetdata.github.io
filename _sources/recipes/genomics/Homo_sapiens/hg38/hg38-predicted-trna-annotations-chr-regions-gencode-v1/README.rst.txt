.. _`hg38-predicted-trna-annotations-chr-regions-gencode-v1`:

hg38-predicted-trna-annotations-chr-regions-gencode-v1
======================================================

|downloads|

Predicted tRNA genes. tRNA genes predicted by ENSEMBL on the reference chromosomes using tRNAscan-SE. This dataset does not form part of the main annotation file.

================================== ====================================
GGD Package                        hg38-predicted-trna-annotations-chr-regions-gencode-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      GENCODE
Data Version                       release-34
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-predicted-trna-annotations-chr-regions-gencode-v1.gtf.gz, hg38-predicted-trna-annotations-chr-regions-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-predicted-trna-annotations-chr-regions-gencode-v1.gtf.gz: **15.37K**, hg38-predicted-trna-annotations-chr-regions-gencode-v1.gtf.gz.tbi: **8.75K**
Package Keywords                   gencode, tRNA, transfer-RNA, annotation, gtf
Package Dependencies:              grch38-chrom-mapping-ucsc2ensembl-ncbi-v1, gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-predicted-trna-annotations-chr-regions-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-predicted-trna-annotations-chr-regions-gencode-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-predicted-trna-annotations-chr-regions-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-predicted-trna-annotations-chr-regions-gencode-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.