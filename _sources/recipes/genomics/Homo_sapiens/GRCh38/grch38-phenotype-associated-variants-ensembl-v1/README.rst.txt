.. _`grch38-phenotype-associated-variants-ensembl-v1`:

grch38-phenotype-associated-variants-ensembl-v1
===============================================

|downloads|

All variants at the time of Ensembl release 99 that have a known phenotype association. Decomposed and Normalized. Ensembl variant info page can be found at: https://uswest.ensembl.org/info/genome/variation/index.html

================================== ====================================
GGD Package                        grch38-phenotype-associated-variants-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-99_11-7-19
Genomic File Type                  vcf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch38-phenotype-associated-variants-ensembl-v1.vcf.gz, grch38-phenotype-associated-variants-ensembl-v1.vcf.gz.tbi
Approximate Size of Each Data File grch38-phenotype-associated-variants-ensembl-v1.vcf.gz: **10.49M**, grch38-phenotype-associated-variants-ensembl-v1.vcf.gz.tbi: **195.40K**
Package Keywords                   genetic-varaition, pheontype-associated, Known-Phenotype, Phenotype-Associated-Variants, VCF, varaint-info, Ensembl-variantion
Package Dependencies:              bcftools, grch38-reference-genome-ensembl-v1, gsort, htslib, vt, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-phenotype-associated-variants-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-phenotype-associated-variants-ensembl-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-phenotype-associated-variants-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-phenotype-associated-variants-ensembl-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.