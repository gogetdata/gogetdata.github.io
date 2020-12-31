.. _`grch37-structural-variants-gnomad-v1`:

grch37-structural-variants-gnomad-v1
====================================

|downloads|

SV callset 2.1 from gnomAD

================================== ====================================
GGD Package                        grch37-structural-variants-gnomad-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      gnomad
Data Version                       2.1.1
Genomic File Type                  vcf
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch37-structural-variants-gnomad-v1.sites.vcf.gz, grch37-structural-variants-gnomad-v1.sites.vcf.gz.tbi
Approximate Size of Each Data File grch37-structural-variants-gnomad-v1.sites.vcf.gz: **140.88M**, grch37-structural-variants-gnomad-v1.sites.vcf.gz.tbi: **452.41K**
Package Keywords                   sv, gnomAD, structural-variants, vcf-file
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-structural-variants-gnomad-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-structural-variants-gnomad-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-structural-variants-gnomad-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-structural-variants-gnomad-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.