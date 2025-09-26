# 'Continually Adapt or Not' or CAN Benchmark

A curated ICICLE benchmark for evaluating the performance of pre-trained models and fostering the development of adaptation algorithms in the camera trap domain.

Tags: Foundation-AI

### License

MIT License. See `LICENSE` for details.

## References
```
Lila bc: Labeled information library of alexandria: Biology and conservation. https://lila.science/. 1, 3
```
## Acknowledgements

*National Science Foundation (NSF) funded AI institute for Intelligent Cyberinfrastructure with Computational Learning in the Environment (ICICLE) (OAC 2112606)*

## Issue reporting
To report any issue(s) with this benchmark, please create an issue in this github or contact: `jeon.193@osu.edu`


---

# How-To Guides

### Data Download
Clone or download the dataset using:

```
git lfs install
git clone https://huggingface.co/datasets/ICICLE-AI/organization-sic-code_smart-foodsheds https://huggingface.co/datasets/ICICLE-AI/CAN_Benchmark 

Then unzip the data archive:
unzip CAN_Benchmark/CDB_D06.zip -d CAN_Benchmark/data
```

### How to use

Please see this link [ICICLE Camera Trap Github](https://github.com/ICICLE-ai/Camera_Trap/), where you can find detailed instruction on how to use this dataset

---
# Explanation
### Dataset Structure
The dataset consists of of two folders:
- `images`: You can find all the images from a camera trap CDB-D06
- `'30'`: You will find three json files in this folder. The whole camera trap dataset has been divided into 30 days interval, for continual learning.
   - `train.json` : Json file for training data divided into 30 days interval.
   - `train-all.json`:Json file containing all training data.
   - `test.json`: Json file containing all test data divided into 30 days interval.

### Dataset Overview

- **Total Size:** ~2.1 TB
- **Total Images:** 3,317,354
- **Regions Covered (17):** apn, cdb, eno, kar, kga, kru, mad, mtz, pln, rua, nz (excluding nz_bad), orinoquia, idaho, serengeti, wellington, caltech, na
- **Number of Cameras:** 546
- **File Format:** JPG
- **Image Resolution Range:** min 56×58, max 1920×2560
- **Average Classes per Dataset:** ~11

### Access

To request access to the full dataset, please contact the maintainers at: **jeon.193@osu.edu**

---
