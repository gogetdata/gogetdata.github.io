.. _`hg19-structural-variants-gnomad-v1`:

hg19-structural-variants-gnomad-v1
==================================

|downloads|

SV callset 2.1 from gnomAD. Remapped from Ensembl GRCh37 to UCSC hg19

================================== ====================================
GGD Package                        hg19-structural-variants-gnomad-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      gnomad
Data Version                       2.1.1
Genomic File Type                  vcf
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg19-structural-variants-gnomad-v1.sites.vcf.gz, hg19-structural-variants-gnomad-v1.sites.vcf.gz.tbi
Approximate Size of Each Data File hg19-structural-variants-gnomad-v1.sites.vcf.gz: **141.05M**, hg19-structural-variants-gnomad-v1.sites.vcf.gz.tbi: **451.90K**
Package Keywords                   sv, gnomAD, structural-variants, vcf-file
Package Dependencies:              gsort, hg19-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-structural-variants-gnomad-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-structural-variants-gnomad-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-structural-variants-gnomad-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-structural-variants-gnomad-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.