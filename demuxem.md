---
layout: default
title: DemuxEM
parent: Hashing demultiplexing
nav_order: 2
---
# DemuxEM

DemuxEM is a tool developped by Pegasus. More information can be found at:
{: .note-title }
> {: .opaque }
> DemuxEM by Pegasus:
> [DemuxEM ](https://pegasus.readthedocs.io/en/stable/api/pegasus.demultiplex.html).


| Parameter   | Description| Example |
|:-------------|:------------------|:------|
| rna_raw | path to raw RNA matrix   | --rna_raw "path/rna_raw/"  |
| hto_matrix  | path to HTO matrix  | --hto_raw /"path/hto_raw/" |
| alpha      | The Dirichlet prior concentration parameter alpha on samples. | --alpha 0.0 |
| alpha_noise  | The Dirichlet prior concenration parameter on the background noise | --alpha_noise 1.0  |
| tol       | Threshold used for the EM convergence | --tol 1e-6 |
| n_threads       | Number of threads to use, must be a positive number | --n_threads 1 |
| min_signal       | Any cell/nucleus with less than min_signal hashtags from the signal will be marked as unknown | --min_signal 10.0|
