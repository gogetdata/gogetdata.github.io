.. _`hg38-knowngene-gene-features-ucsc-v1`:

hg38-knowngene-gene-features-ucsc-v1
====================================

|downloads|

Gene features from the &#39;KnownGene&#39; track from UCSC. (GTF). Features include 5UTR, 3UTR, CDS, exon, start_codon, stop_codon, transcript. Features are comprised of all gene models from GENCODE v32. IDs correspond to the UCSC knowGene IDs.

================================== ====================================
GGD Package                        hg38-knowngene-gene-features-ucsc-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      UCSC
Data Version                       10-Jan-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-knowngene-gene-features-ucsc-v1.gtf.gz, hg38-knowngene-gene-features-ucsc-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-knowngene-gene-features-ucsc-v1.gtf.gz: **35.47M**, hg38-knowngene-gene-features-ucsc-v1.gtf.gz.tbi: **339.94K**
Package Keywords                   KnownGenes, gene-features, UCSC-Genes, feature-file, gene-feature-file, 5UTR, 3UTR, CDS, exon, start_codon, stop_codon, transcript, GTF, GENCODE-v32-genes
Package Dependencies:              gsort, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-knowngene-gene-features-ucsc-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-knowngene-gene-features-ucsc-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-knowngene-gene-features-ucsc-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-knowngene-gene-features-ucsc-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.