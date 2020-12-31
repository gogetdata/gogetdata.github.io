.. _`hg19-exome-variants-gnomad-v1`:

hg19-exome-variants-gnomad-v1
=============================

|downloads|

SNV and INDEL varaints from 125,748 exomes in the gnomAD dataset version 2.1.1 in bcf format. The file constains all subsets of non-neuro, non-cancer, controls-only, and non-TOPMed samples. Remapped from Ensembl GRCh37 to UCSC hg19

================================== ====================================
GGD Package                        hg19-exome-variants-gnomad-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      gnomAD
Data Version                       v2.1.1
Genomic File Type                  bcf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg19-exome-variants-gnomad-v1.bcf, hg19-exome-variants-gnomad-v1.bcf.csi
Approximate Size of Each Data File hg19-exome-variants-gnomad-v1.bcf: **28.98G**, hg19-exome-variants-gnomad-v1.bcf.csi: **707.78K**
Package Keywords                   gnomAD, variants, population-variation, Genome-Aggergation-Database
Package Dependencies:              bcftools, gsort, hg19-chrom-mapping-ensembl2ucsc-ncbi-v1, hg19-reference-genome-ucsc-v1
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-exome-variants-gnomad-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-exome-variants-gnomad-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-exome-variants-gnomad-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-exome-variants-gnomad-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.