.. _`danrer10-reference-genome-ucsc-v1`:

danrer10-reference-genome-ucsc-v1
=================================

|downloads|

The danRer10 reference genome from UCSC

================================== ====================================
GGD Package                        danrer10-reference-genome-ucsc-v1 
Species                            Danio_rerio
Genome Build                       danRer10
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NA
Data Version                       1/29/15
Genomic File Type                  NA
Data file coordinate basing        NA
Package's Data Files               NA
Approximate Size of Each Data File NA
Package Keywords                   ref, reference, zebrafish, genome, UCSC, fasta-file
Package Dependencies:              samtools, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Danio_rerio/danRer10/danrer10-reference-genome-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *False*. This package has not been set up to use the ``--prefix`` flag when running ggd install. Once installed, this package will work with other ggd tools that use ``--prefix`` flag.

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics danrer10-reference-genome-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/danrer10-reference-genome-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/danrer10-reference-genome-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.