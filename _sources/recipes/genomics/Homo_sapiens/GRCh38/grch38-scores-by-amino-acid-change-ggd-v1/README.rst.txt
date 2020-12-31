.. _`grch38-scores-by-amino-acid-change-ggd-v1`:

grch38-scores-by-amino-acid-change-ggd-v1
=========================================

|downloads|

Scores for each amino acid changes from missense badnass, blosum, and granthams

================================== ====================================
GGD Package                        grch38-scores-by-amino-acid-change-ggd-v1 
Species                            Homo_sapiens
Genome Build                       GRCh38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      ggd
Data Version                       1
Genomic File Type                  txt
Data file coordinate basing        NA
Package's Data Files               grch38-scores-by-amino-acid-change-ggd-v1.txt
Approximate Size of Each Data File grch38-scores-by-amino-acid-change-ggd-v1.txt: **4.86K**
Package Keywords                   amion-acid, amino-acid-change, constraint, missense-badness-score, blosum-score, granthams-score, amino-acid-score
Package Dependencies:              
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/GRCh38/grch38-scores-by-amino-acid-change-ggd-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics grch38-scores-by-amino-acid-change-ggd-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/grch38-scores-by-amino-acid-change-ggd-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/grch38-scores-by-amino-acid-change-ggd-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.