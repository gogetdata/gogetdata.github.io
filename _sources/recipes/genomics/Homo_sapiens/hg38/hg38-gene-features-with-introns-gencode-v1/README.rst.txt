.. _`hg38-gene-features-with-introns-gencode-v1`:

hg38-gene-features-with-introns-gencode-v1
==========================================

|downloads|

Comprehensive set of gene anntotations including reference chromosomes, scaffoldings, assebly patches, and alternative loci. Intron features for each transcripts have been added to the annotation set. Data is specific to GENCODE Release 34 (Ensembl 100). Features include: gene, transcript, exon, intron, CDS, UTR, start_codon, stop_codon, and Selenocysteine. Remapped from Ensembl GRCh38 to UCSC hg38. (Scaffoldings wihtout UCSC matches are kept with Ensebml ids)

================================== ====================================
GGD Package                        hg38-gene-features-with-introns-gencode-v1 
Species                            Homo_sapiens
Genome Build                       hg38
GGD Channel                        ggd-genomics
Package Version                    1
Recipe Author                      mjc 
Data Provider                      GENCODE
Data Version                       release-34_03-24-2020
Genomic File Type                  gtf
Data file coordinate basing        1-based-inclusive
Package's Data Files               hg38-gene-features-with-introns-gencode-v1.gtf.gz, hg38-gene-features-with-introns-gencode-v1.gtf.gz.tbi
Approximate Size of Each Data File hg38-gene-features-with-introns-gencode-v1.gtf.gz: **77.00M**, hg38-gene-features-with-introns-gencode-v1.gtf.gz.tbi: **288.63K**
Package Keywords                   Gene-Features, Gene-Annotations, All-Regions, GTF, GENOCDOE-GTF, GENCODE-Gene-Sets, Annotated-Transcripts, Intron-Features, Introns
Package Dependencies:              gsort, hg38-chrom-mapping-ensembl2ucsc-ncbi-v1, htslib, zlib
Recipe                             https://github.com/gogetdata/ggd-recipes/tree/master/recipes/genomics/Homo_sapiens/hg38/hg38-gene-features-with-introns-gencode-v1
================================== ====================================

Install with ``--prefix``
-------------------------
**Prefix install enabled:** *True*

Installation
------------

.. highlight: bash

With ggd installed and an activated ggd channel (see :ref:`using-ggd`), install with::

   ggd install -c ggd-genomics hg38-gene-features-with-introns-gencode-v1

.. |downloads| image:: https://anaconda.org/ggd-genomics/hg38-gene-features-with-introns-gencode-v1/badges/downloads.svg
               :target: https://anaconda.org/ggd-genomics/hg38-gene-features-with-introns-gencode-v1