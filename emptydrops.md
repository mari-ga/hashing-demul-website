---
layout: default
title: Empty Drops
nav_order: 2
has_children: false
---

# Empty Drops
Empty Drops is a filtering tool part of the library Droplet Utils. More information can be found at:
{: .note-title }
> {: .opaque }
> Empty Drops by Droplet Utils:
> [Empty Drops ](https://rdrr.io/github/MarioniLab/DropletUtils/man/emptyDrops.html).


| Parameter   | Description| Example |
|:-------------|:------------------|:------|
| hto_raw  | path to filtered HTO matrix | --hto_raw /"path/hto_raw/"  |
| niters | specifies the number of iterations to use for the Monte Carlo p-value calculations | --niters 10000  |
| lower  | specifies the lower bound on the total UMI count, at or below which all barcodes are assumed to correspond to empty droplets  | --lower 100.  |
| testAmbient  |  indicates whether results should be returned for barcodes with totals less than or equal to lower | --testAmbient FALSE |
| alpha_empty  |specifies the scaling parameter for the Dirichlet-multinomial sampling scheme | --alpha_empty NULL |
| ignore  | specifies the lower bound on the total UMI count, at or below which barcodes will be ignored  | --ignore NULL |

The description of this parameters were provided by the library. They can also be found in the link above.