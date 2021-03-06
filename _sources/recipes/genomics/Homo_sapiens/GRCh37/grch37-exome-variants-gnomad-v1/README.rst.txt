.. _`grch37-exome-variants-gnomad-v1`:

grch37-exome-variants-gnomad-v1
===============================

|downloads|

SNV and INDEL varaints from 125,748 exomes in the gnomAD dataset version 2.1.1 in bcf format. The file constains all subsets of non-neuro, non-cancer, controls-only, and non-TOPMed samples.

================================== ====================================
GGD Package                        grch37-exome-variants-gnomad-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      gnomAD
Data Version                       v2.1.1
Genomic File Type                  bcf
Data file coordinate basing        1-based-inclusive
Package's Data Files               grch37-exome-variants-gnomad-v1.bcf, grch37-exome-variants-gnomad-v1.bcf.csi
Approximate Size of Each Data File grch37-exome-variants-gnomad-v1.bcf: **28.98G**, grch37-exome-variants-gnomad-v1.bcf.csi: **708.01K**
Package Keywords                   gnomAD, variants, population-variation, Genome-Aggergation-Database
Package Dependencies:              bcftools, gsort
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-exome-variants-gnomad-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-exome-variants-gnomad-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-exome-variants-gnomad-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-exome-variants-gnomad-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.