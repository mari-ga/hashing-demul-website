---
layout: default
title: HTODemux
parent: Hashing demultiplexing
nav_order: 2
---
# HTODemux

HTODemux is a tool for Hashing Demultiplexing created by Seurat. More information can be found at:
{: .note-title }
> {: .opaque }
> HTODemux by Seurat:
> [HTODemux ](https://satijalab.org/seurat/articles/hashing_vignette.html).


## Parameters - Pre processing

| Parameter   | Description| Example |
|:-------------|:------------------|:------|
| umi  | path to filtered rna matrix | --umi /"path/rna_filtered/"  |
| hto_matrix | path to filtered hto matrix   | --umi "/path/hto_filtered/"  |
| selection_method  | How to choose top variable features      | --selection_method "mean.var.plot"  |
| ndelim      | delimiter from the cell's column nam | --ndelim "_"  |
| number_features  | Number of features to be used when finding variable features | --number_features 2000  |
| assay       | Choose assay between RNA or HTO | --assay "HTO" |
| margin      | Margin for normalisation | --margin 2  |
| norm_method | Normalisation method | --norm_method "CLR" |

## Parameters - Demultiplexing

| Parameter   | Description| Example |
|:-------------|:------------------|:------|
| quantile | quantile for classification  | --quantile_hto 0.99  |
| kfunc  | clustering function  | --kfunc "clara" |
| nstarts      | nstarts value for k-means clustering | --nstarts 100 |
| nsamples  | Number of samples to be drawn from the dataset used for clustering for kfunc clara | --nsamples 100  |
| init       | Initial number of clusters for hashtags | --init NULL |
