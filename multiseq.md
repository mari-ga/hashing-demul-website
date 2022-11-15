---
layout: default
title: MULTI-seq
parent: Hashing demultiplexing
nav_order: 2
---
# MULTI-seq

MULTI-seq is a tool for Hashing Demultiplexing created by Seurat. More information can be found at:
{: .note-title }
> {: .opaque }
> HTODemux by Seurat:
> [MULTI-seq ](https://satijalab.org/seurat/reference/multiseqdemux).


## Parameters - Pre processing
These are the same parameters already given for HTODemux, it is not necessary to give them twice for the execution of the pipeline.

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
| quantile_multi |quantile for classification| --quantile_hto 0.07  |
| autoThresh | Whether to perform automated threshold finding to define the best quantile  | --autoThresh "FALSE" |
| maxiter   | Maximum number of iterations if autoThresh = TRUE | --maxiter 5 |
| qrangeFrom  | Lower quantile | --qrangeFrom 0.1  |
| qrangeTo       | Upper quantile | --qrangeTo 0.9 |
| qrangeBy       | Step to increase/reduce quantile | --qrangeBy 0.0.05 |
