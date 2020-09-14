.. _`hg38-sequence-1000g-v1`:

hg38-sequence-1000g-v1
======================

|downloads|

Full hg38/GRCh38 reference genome distributed by 1000 genomes Derived from NCBI set with HLA and decoy alternative alleles ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/reference/GRCh38_reference_genome/

================================== ====================================
GGD Package                        hg38-sequence-1000g-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NA
Data Version                       1000g - 3/8/15
Genomic File Type                  NA
Data file coordinate basing        NA
Package's Data Files               NA
Approximate Size of Each Data File NA
Package Keywords                   sequence, 1000g, fasta-file
Package Dependencies:              
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-sequence-1000g-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *False*. This package has not been set up to use the ``--prefix`` flag when running ggd install. Once installed, this package will work with other ggd tools that use ``--prefix`` flag.

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-sequence-1000g-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-sequence-1000g-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-sequence-1000g-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.