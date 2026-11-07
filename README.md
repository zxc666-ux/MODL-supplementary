# MODL-Net supplementary data

Scenario-ID lists and SHA-256 checksums for the Argoverse 2 intersection subsets used in:

**Maneuver-Aware History and Ordered Directional Lane Representations for Multimodal Trajectory Prediction at Urban Intersections**

Authors: Jianhua Zhang and Shichang Zhang  
Journal: Applied Intelligence  
Affiliation: College of Civil Engineering and Transportation, Northeast Forestry University, Harbin 150040, China  
Corresponding author: Jianhua Zhang, jhzhang609@nefu.edu.cn

## Online Resource 1

Download [ESM_1.zip](ESM_1.zip), or use the versioned archive attached to the repository release.

| Partition | File | Scenarios |
| --- | --- | ---: |
| Training | `train_scenario_ids.txt` | 60,899 |
| Validation | `val_scenario_ids.txt` | 7,627 |
| Test | `test_scenario_ids.txt` | 7,704 |

The archive also contains `README.txt` and `SHA256SUMS.txt`. Each scenario list has one ID per line. The three lists are disjoint. The partition names refer to the original AV2 partitions. The filtering procedure is described in Section 5.1 of the manuscript.

## Data source and verification

Obtain trajectories, maps, and annotations from the [Argoverse 2 project](https://www.argoverse.org/av2.html) under the original distributor's terms. This repository provides the subset identifiers and checksums.

After extracting the archive, verify the lists with `sha256sum -c SHA256SUMS.txt`.

SHA-256 of `ESM_1.zip`:

```
b3f37fe5cc7c52ae9ddb11d9aa53e2bc781507d8a42a8d383acd36b792832eaa
```

## Code availability

The code will be made publicly available upon acceptance.
