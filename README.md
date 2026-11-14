# MODL-Net supplementary data

Scenario-ID lists and SHA-256 checksums for the Argoverse 2 intersection subsets used in:

**Manoeuvre-Aware History and Ordered Directional Lane Representations for Multimodal Trajectory Prediction at Urban Intersections**

Authors: Jianhua Zhang and Shichang Zhang  
Affiliation: College of Civil Engineering and Transportation, Northeast Forestry University, Harbin 150040, China  
Corresponding author: Jianhua Zhang, jhzhang609@nefu.edu.cn

## Supplemental material

Download [Supplemental_Material_ScenarioIDs.zip (v1.1)](https://github.com/zxc666-ux/MODL-supplementary/releases/download/v1.1/Supplemental_Material_ScenarioIDs.zip). See the [v1.1 release](https://github.com/zxc666-ux/MODL-supplementary/releases/tag/v1.1) for the versioned record.

| Partition | File | Scenarios |
| --- | --- | ---: |
| Training | `train_scenario_ids.txt` | 60,899 |
| Validation | `val_scenario_ids.txt` | 7,627 |
| Test | `test_scenario_ids.txt` | 7,704 |

The archive also contains `README.txt` and `SHA256SUMS.txt`. Each line of a list is a cached file name in the form `scenario_<AV2 scenario ID>.pt`. The three lists are disjoint. The partition names refer to the original AV2 partitions. The filtering procedure is described in Section 5.1 of the manuscript.

Version 1.1 updates the archive name and manuscript information for the Transportmetrica B submission. The three scenario lists and their checksums are unchanged from [v1.0](https://github.com/zxc666-ux/MODL-supplementary/releases/tag/v1.0), which remains available.

## Data source and verification

Obtain trajectories, maps, and annotations from the [Argoverse 2 project](https://www.argoverse.org/av2.html) under the original distributor's terms. This repository provides the subset identifiers and checksums.

After extracting the archive, verify the lists with `sha256sum -c SHA256SUMS.txt`.

SHA-256 of `Supplemental_Material_ScenarioIDs.zip`:

```text
20aa6bb23abc9c1d7a4a063b66b13f0f01c263bf960462e3a4b2eca7ac0e675d
```

## Code availability

The code will be made publicly available upon acceptance.
