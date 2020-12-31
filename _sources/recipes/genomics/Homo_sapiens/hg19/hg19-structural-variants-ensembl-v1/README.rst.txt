.. _`hg19-structural-variants-ensembl-v1`:

hg19-structural-variants-ensembl-v1
===================================

|downloads|

All known structural mutations at the time of Ensembl release 75. Remapped from Ensembl GRCh37 to UCSC hg19. Ensembl variant info page can be found at: https://uswest.ensembl.org/info/genome/variation/index.html

================================== ====================================
GGD Package                        hg19-structural-variants-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-75_2-9-14
Genomic File Type                  vcf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg19-structural-variants-ensembl-v1.vcf.gz, hg19-structural-variants-ensembl-v1.vcf.gz.tbi
Approximate Size of Each Data File hg19-structural-variants-ensembl-v1.vcf.gz: **101.41M**, hg19-structural-variants-ensembl-v1.vcf.gz.tbi: **308.95K**
Package Keywords                   genetic-varaition, SV, structural-mutations, structural-variants, VCF, varaint-info, Ensembl-variantion
Package Dependencies:              bcftools, gsort, hg19-chrom-mapping-ensembl2ucsc-ncbi-v1, hg19-reference-genome-ucsc-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-structural-variants-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-structural-variants-ensembl-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-structural-variants-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-structural-variants-ensembl-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.