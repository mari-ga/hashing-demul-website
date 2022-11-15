---
layout: default
title: Hashed Drops
parent: Hashing demultiplexing
nav_order: 2
---
# Hashed Drops

Hashed Drops is a demultiplexing tool part of the library Droplet Utils. More information can be found at:
{: .note-title }
> {: .opaque }
> Hashed Drops by Droplet Utils:
> [Hashed Drops ](https://rdrr.io/github/MarioniLab/DropletUtils/man/hashedDrops.html).

| Parameter   | Description| Example |
|:-------------|:------------------|:------|
| hashtag_data | path to filtered HTO matrix   | --hashtag_data "path/hto_filtered/"   |
|rawData| TRUE if the HTO matrix is raw data to execute hashed drops first | --rawData FALSE |
| ambient  | Only available when the dataset specifies the relative abundance of each HTO in the ambient solution (results from empty drops), otherwise keep in NULL | --ambient "NULL"  |
| minProp |Numeric scalar to be used to infer the ambient profile when ambient=NULL | --minProp 0.05 |
| pseudoCount       |  minimum pseudo-count when computing log-fold changes. | --pseudoCount 5 |
| constAmbient       | Indicates whether a constant level of ambient contamination should be used to estimate LogFC2 for all cell | --constAmbient FALSE|
| doubletMin       | Specifies the minimum threshold on the log-fold change to use to identify doublets | --doubletMin 2|
| doubletNmads       | specifies the number of median absolute deviations (MADs) to use to identify doublets. | --doubletNmads 3|
| confidenMin       |  specifying the minimum threshold on the log-fold change to use to identify singlet | --confidenMin 2|
| confidentNmads       | specifies the number of MADs to use to identify confidently assigned singlets | --confidentNmads 3|

The description of this parameters were provided by the library. They can also be found in the link above.