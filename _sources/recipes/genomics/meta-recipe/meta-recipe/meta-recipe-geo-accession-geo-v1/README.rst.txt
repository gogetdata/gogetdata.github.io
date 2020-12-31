.. _`meta-recipe-geo-accession-geo-v1`:

meta-recipe-geo-accession-geo-v1
================================

|downloads|

A meta-recipe for the Gene Expression Omnibus (GEO) database from NCBI. This meta-recipe contains the instructions for accessing GEO data using GEO Accession IDs. GEO Datasets (GDS), GEO Platforms (GPL), GEO Series (GSE), and GEO Samples (GSM) are all accessible through this meta-recipe. Files downloaded for each type are: (GDS) SOFT files. (GPL) SOFT files and ANNOT files if they exist. (GSE) SOFT file and MATRIX files if they exist. (GSM) The main table file as a .txt file. Additionally, for all 4 types, all supplemental files are downloaded if they exist. Once installed, GEO ID specific recipes will contain ID specific info, such as a summary of the data and a url to the GEO Accession ID specific page. This info can be accessed using &#39;ggd pkg-info&#39;. To install simply add the &#39;--id&#39; flag with the desired GEO Accession ID when running &#39;ggd install&#39;. Additional info about GEO can be found at http://www.ncbi.nlm.nih.gov/geo

================================== ====================================
GGD Package                        meta-recipe-geo-accession-geo-v1 
Species                            meta-recipe
Genome Build                       meta-recipe
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GEO
Data Version                       meta-recipe
Genomic File Type                  
Data file coordinate basing        NA
Package's Data Files               
Approximate Size of Each Data File 
Package Keywords                   Gene-Expression-Omnibus, GEO, GEO-Accession-ID, GEO-meta-recipe
Package Dependencies:              
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/meta-recipe/meta-recipe/meta-recipe-geo-accession-geo-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics meta-recipe-geo-accession-geo-v1 --id <Specific ID>

.. |downloads| image:: https://anaconda.org/ggd-genomics/meta-recipe-geo-accession-geo-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/meta-recipe-geo-accession-geo-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.