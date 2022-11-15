---
layout: default
title: Solo
nav_order: 2
has_children: false
---

# Solo
Solo is a doublet detection tool, developped by Calico, moved to SCVI-tools. More information can be found at:
{: .note-title }
> {: .opaque }
> Solo implementation by SCVI-tools:
> [Solo ](https://docs.scvi-tools.org/en/stable/api/reference/scvi.external.SOLO.html).


| Parameter   | Description| Example |
|:-------------|:------------------|:------|
| doublet_detection  | TRUE to execute solo | --doublet_detection TRUE  |
| umi_count  | path to HTO matrix, same as HTODemux, no need to repeat| --umi_count /"path/hto_filtered/"  |
| soft  | True to return probabilities instead of class label | --soft False  |
| max_epochs | probability for negatives  | --max_epochs 100 |
| lr  | learning rate  | --lr 0.001  |



The description of this parameters were provided by the library. They can also be found in the link above.