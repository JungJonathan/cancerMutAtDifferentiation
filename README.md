# cancerMutAtDifferentiation

A repository of the analysis and presentation of cancer-related mutations during differentiation.


## Pre-requisitions
Built over elyadlezmi/RNA2CM pipeline, this pipeline can deal autonomously with much more RNA-seq data.
As such, it is necessary to meet the RNA2CM criteria.

## Installation
Downloading the scripts should be as one directory, without switching file positions.
In addition, the following files must be added in the specific paths:
 - COSMICXXX.csv -> cancerMutAtDifferentiation/data/
 - ...

## Usage
Firstly, create a file named CuratedMetaData.csv including the following columns:
 - Accession
 - LibreryLayout
 - ...

*The data can be mostly gathered from the SRA Run Selector*

After RNA2CM pipeline has been done, run Analysis.py to get summarized data of mutations in three files:
 - Mutations.csv
 - AcquiredMutations.csv
 - SummarizedXXX.csv

Next, run figures.R and receive the results in understandable visual context.

