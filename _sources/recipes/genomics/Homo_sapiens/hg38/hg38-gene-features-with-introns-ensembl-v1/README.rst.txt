.. _`hg38-gene-features-with-introns-ensembl-v1`:

hg38-gene-features-with-introns-ensembl-v1
==========================================

|downloads|

Gene features, including all annotated transcripts, that make up the Ensembl gene sets. Intron features for each transcripts have been added to the annotation set. (Alignment based annotation using proteins, cDNA, RNA-seq, etc.). Features include: CDS, Selenocysteine, UTR, exon, gene, intron, start_codon, stop_codon, and  transcript. Features are in GTF format. Remapped from Ensembl GRCh38 to UCSC hg38

================================== ====================================
GGD Package                        hg38-gene-features-with-introns-ensembl-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      Ensembl
Data Version                       release-100_3-7-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-gene-features-with-introns-ensembl-v1.gtf.gz, hg38-gene-features-with-introns-ensembl-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-gene-features-with-introns-ensembl-v1.gtf.gz: **72.41M**, hg38-gene-features-with-introns-ensembl-v1.gtf.gz.tbi: **260.51K**
Package Keywords                   Gene-Features, GTF, Ensembl-GTF, Ensembl-Gene-Set, Annotated-Transcripts, Intron-Features, Introns
Package Dependencies:              gsort, hg38-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-gene-features-with-introns-ensembl-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c genomics hg38-gene-features-with-introns-ensembl-v1 

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-gene-features-with-introns-ensembl-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-gene-features-with-introns-ensembl-v1

Activating Environment Variables
--------------------------------

Run :code:`source activate base` after installing the data package to activate the environment variables 
associated with this data package.

.. note::
    
    You must be in the conda environment where the data package was installed in order to use the 
    associated environment variables. Otherwise, use :code:`ggd get-files` to access this package's
    data files.