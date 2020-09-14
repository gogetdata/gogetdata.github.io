.. _`hg38-phastcons-ucsc-v1`:

hg38-phastcons-ucsc-v1
======================

|downloads|

Conservation scores based on the phastcons HMM algorithm against multi-aligned sequences of 100 different species

================================== ====================================
GGD Package                        hg38-phastcons-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       08-May-2015
Genomic File Type                  bedGraph.gz, bedGraph.gz.tbi, bw
Data file coordinate basing        0-based-inclusive
Package's Data Files               hg38-phastcons-ucsc-v1.bedGraph.gz, hg38-phastcons-ucsc-v1.bedGraph.gz.tbi, hg38-phastcons-ucsc-v1.bw
Approximate Size of Each Data File hg38-phastcons-ucsc-v1.bedGraph.gz: **11.97G**, hg38-phastcons-ucsc-v1.bedGraph.gz.tbi: **7.28K**, hg38-phastcons-ucsc-v1.bw: **5.89G**
Package Keywords                   phastCons, conservation, phastCons-Hmm, conservation-scores, genome-conservation, bigwig, bedgraph
Package Dependencies:              gsort, htslib, ucsc-bigwigtobedgraph, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-phastcons-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-phastcons-ucsc-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-phastcons-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-phastcons-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.