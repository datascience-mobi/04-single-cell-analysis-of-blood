Single cell analysis of blood
===================================

#### Project overview and guidelines

-   [Introduction](#introduction)
-   [Objective](#objective)
-   [Description of datasets](#description-of-datasets)
-   [Literature review](#literature-review)
-   [Project](#project)

Supervisors
------------

-   Thorsten Beier
    ([thorsten.beier@embl.de](mailto:thorsten.beier@embl.de))

Introduction
------------

This project is based on the seurat tutorial
([https://satijalab.org/seurat/pbmc3k\_tutorial.html](https://satijalab.org/seurat/pbmc3k_tutorial.html))
Here we try to replicate the relevant steps of the tutorial without
using the Seurat library (except for the data-loading) We will be
analyzing the a dataset of Peripheral Blood Mononuclear Cells. The
analysis consists of Standard pre-processing workflows like the
normalization of data and simple analysis like dimension reduction.

Objective
---------

The objective of this project is to achieve the following:

We want to replicate the Seurat Guided Clustering Tutorial. This
constists of the following steps:

Easy Steps:

-   Loading the data
-   Normalizing the data
-   Detection of variable genes across the single cells
-   Scaling the data and removing unwanted sources of variation
-   Perform linear dimensional reduction
-   Determine statistically significant principal components

Advanced steps:

-   Cluster the cells
-   Run Non-linear dimensional reduction (tSNE)
-   Finding differentially expressed genes (cluster biomarkers)
-   Assigning cell type identity to clusters

Each of the individual step is explained in detail at
[https://satijalab.org/seurat/pbmc3k\_tutorial.html](https://satijalab.org/seurat/pbmc3k_tutorial.html)

Description of datasets
-----------------------

For this project, we will be analyzing the a dataset of Peripheral Blood
Mononuclear Cells (PBMC) freely available from 10X Genomics. There are
2,700 single cells that were sequenced on the Illumina NextSeq 500.

Literature review
-----------------

#### Reviews

Read these papers for more details:

-   (Macosko, Basu, Satija et al., Cell, 2015)
-   (Satija*, Farrell* et al., Nature Biotechnology, 2015)
-   (Butler et al., Nature Biotechnology, 2018)

Project
-------

You project **MUST** contain the following elements:

-   *descriptive statistics* about the datasets, including *graphical
    representations*
-   normalization of the data
-   cleaning the data
-   a *dimension reduction* analysis
-   interpretation of the results
