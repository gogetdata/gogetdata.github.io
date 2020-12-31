.. _`grch37-hg002-svs-giab-v1`:

grch37-hg002-svs-giab-v1
========================

|downloads|

SV callset for the Ashkenazi trio son HG002 in grch37

================================== ====================================
GGD Package                        grch37-hg002-svs-giab-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      jrb 
Data Provider                      giab
Data Version                       0.6
Genomic File Type                  vcf
Data file coordinate basing        0-based-inclusive
Package's Data Files               grch37-hg002-svs-giab-v1.6.sorted.vcf.gz, grch37-hg002-svs-giab-v1.6.sorted.vcf.gz.tbi
Approximate Size of Each Data File grch37-hg002-svs-giab-v1.6.sorted.vcf.gz: **25.50M**, grch37-hg002-svs-giab-v1.6.sorted.vcf.gz.tbi: **451.75K**
Package Keywords                   sv, nist, structural-variants, sv, structural, vcf-file, giab, ashkenazi, na24385, hg002, trio, son
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-hg002-svs-giab-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-hg002-svs-giab-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-hg002-svs-giab-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-hg002-svs-giab-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.