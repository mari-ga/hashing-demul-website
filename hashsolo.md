---
layout: default
title: Hash Solo
parent: Hashing demultiplexing
nav_order: 2
---
# Hash Solo
Hash Solo is a demultiplexing tool, developped by Calico. More information can be found at:
{: .note-title }
> {: .opaque }
> Hash Solo by Calico:
> [Hash Solo ](https://github.com/calico/solo).

| Parameter   | Description| Example |
|:-------------|:------------------|:------|
| hto_data  | path to filtered rna matrix | --umi /"path/rna_filtered/"  |
| priors_negative | probability for negatives  | --priors_negative 0.33  |
| priors_singlet  | probability for singlets  | --priors_singlet 0.33  |
| priors_doublet  | probability for doublets | --priors_doublet 0.33 |

The description of this parameters were provided by the library. They can also be found in the link above.