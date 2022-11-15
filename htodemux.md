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
| sel_method  | How to choose top variable features      | --sel_method "mean.var.plot"  |
| ndelim      | delimiter from the cell's column nam | --ndelim "_"  |
| n_features  | Number of features to be used when finding variable features | --n_features 2000  |
| assay       | Choose assay between RNA or HTO | --assay "HTO" |
| margin      | Margin for normalisation | --margin 2  |
| norm_method | Normalisation method | --norm_method "CLR" |