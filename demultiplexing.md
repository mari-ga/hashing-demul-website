---
layout: default
title: Hashing demultiplexing
nav_order: 2
has_children: true
---

# Hashing Demultiplexing

## Input files
In order to use the hashing demultiplexing section, you will need the following files:

| File      | Format         | Type |
|:-------------|:------------------|:------|
| HTO matrix | 10x folder | filtered matrix |
| HTO matrix | h5         | raw matrix |
| HTO matrix | 10x folder | raw matrix|
| RNA matrix | 10x folder | filtered matrix|

## Execution example

`<nextflow run main.nf --normalisation_method "CLR" --quantile_hto 0.8 --quantile_multi 0.8 --maxiter 10 --qrangeFrom 0.2 --qrangeTo 0.7 --ridgePlot TRUE --vlnplot TRUE --vlnFeatures "nCount_RNA" --featureScatter TRUE --scatterFeat1 "Hash453-TotalSeqA" --scatterFeat2 "Hash451-TotalSeqA" --constAmbient TRUE --confidenMin 1 --doubletMin 1 --confidentNmads 0.6 --min_signal 11.0 --tsne TRUE --tsneDimMax 6 --doublet_detection FALSE --cleaning_raw FALSE >`