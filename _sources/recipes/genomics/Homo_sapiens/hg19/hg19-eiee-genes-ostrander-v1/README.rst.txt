.. _`hg19-eiee-genes-ostrander-v1`:

hg19-eiee-genes-ostrander-v1
============================

|downloads|

CDS region genomic coordinates, along with complement coordinates, for a set of eiee genes. The eiee gene set comes from a paper on EIEE (Early Infantile Epileptic Encephalopathy) a severe, fatal epileptic syndrome that occurs within the first few months of life. The gene set is a compilation of gene sets from a few different companies, gene panels, as well as one from the U of Chicago. Paper at: https://www.nature.com/articles/s41525-018-0061-8

================================== ====================================
GGD Package                        hg19-eiee-genes-ostrander-v1 
Species                            Homo_sapiens
Genome Build                       hg19
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ostrander
Data Version                       13-Aug-2018
Genomic File Type                  bed
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg19-eiee-genes-ostrander-v1.bed.gz, hg19-eiee-genes-ostrander-v1.bed.gz.tbi, hg19-eiee-genes-ostrander-v1.complement.bed.gz, hg19-eiee-genes-ostrander-v1.complement.bed.gz.tbi
Approximate Size of Each Data File hg19-eiee-genes-ostrander-v1.bed.gz: **48.78K**, hg19-eiee-genes-ostrander-v1.bed.gz.tbi: **14.85K**, hg19-eiee-genes-ostrander-v1.complement.bed.gz: **30.71K**, hg19-eiee-genes-ostrander-v1.complement.bed.gz.tbi: **11.01K**
Package Keywords                   eiee, early-infantile, epileptic, epilepsy, encephalopathy, ostrander, genes, gene-set
Package Dependencies:              bedtools, grch37-gene-features-ensembl-v1, gsort, hg19-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, pyexcel, pyexcel-xls, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg19/hg19-eiee-genes-ostrander-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg19-eiee-genes-ostrander-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg19-eiee-genes-ostrander-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg19-eiee-genes-ostrander-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.