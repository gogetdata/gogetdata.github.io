.. _`grch37-chrom-mapping-ensembl2refseq-ncbi-v1`:

grch37-chrom-mapping-ensembl2refseq-ncbi-v1
===========================================

|downloads|

A tab delimited file containing scaffolding ids that maps GRCh37 Ensembl(GenBank) scaffoldings to GRCh37 RefSeq scaffoldings. This is specific to patch 13 of the GRCh37 Human genome build. (1st column = Ensembl ids, 2nd column = RefSeq ids)

================================== ====================================
GGD Package                        grch37-chrom-mapping-ensembl2refseq-ncbi-v1 
Species                            Homo_sapiens
Genome Build                       GRCh37
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      NCBI
Data Version                       12-October-2016-(patch13)
Genomic File Type                  txt
Data file coordinate basing        NA
Package's Data Files               grch37-chrom-mapping-ensembl2refseq-ncbi-v1.txt
Approximate Size of Each Data File grch37-chrom-mapping-ensembl2refseq-ncbi-v1.txt: **7.27K**
Package Keywords                   Chromosome-mapping, mapping, chrommapping, Ensembl2RefSeq, scaffolding-ids, txt, patch-13
Package Dependencies:              bioawk
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh37/grch37-chrom-mapping-ensembl2refseq-ncbi-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch37-chrom-mapping-ensembl2refseq-ncbi-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch37-chrom-mapping-ensembl2refseq-ncbi-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch37-chrom-mapping-ensembl2refseq-ncbi-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.