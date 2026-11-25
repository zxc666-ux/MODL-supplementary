# MODL-Net supplementary data

Scenario-ID lists and SHA-256 checksums for the Argoverse 2 intersection subsets used in:

**MODL-Net: Maneuver-Aware History and Ordered Directional Lane Encoding for Streaming Trajectory Prediction at Urban Intersections**

Authors: Jianhua Zhang and Shichang Zhang  
Affiliation: College of Civil Engineering and Transportation, Northeast Forestry University, Harbin 150040, China  
Corresponding author: Jianhua Zhang, jhzhang609@nefu.edu.cn

## Supplementary material

Download `Supplementary_Material_ScenarioIDs.zip` from the [latest repository release](https://github.com/zxc666-ux/MODL-supplementary/releases/latest).

| Partition | File | Scenarios |
| --- | --- | ---: |
| Training | `train_scenario_ids.txt` | 60,899 |
| Validation | `val_scenario_ids.txt` | 7,627 |
| Test | `test_scenario_ids.txt` | 7,704 |

The archive also contains `README.txt` and `SHA256SUMS.txt`. Each line of a list is a cached file name in the form `scenario_<AV2 scenario ID>.pt`. The three lists are disjoint. The partition names refer to the original AV2 partitions. The filtering procedure is described in Section IV-A of the manuscript.

## Data source and verification

Obtain trajectories, maps, and annotations from the [Argoverse 2 project](https://www.argoverse.org/av2.html) under the original distributor's terms. This repository provides the subset identifiers and checksums.

After extracting the archive, verify the lists with `sha256sum -c SHA256SUMS.txt`.

## Code availability

The code will be made publicly available upon acceptance.
