# WEED6C Dataset

Corn weed image dataset

![fig2](https://github.com/user-attachments/assets/10568105-407b-4369-920b-28a517d393ac)

## Image Collection

During the 2021/22 harvest, UAV flights were conducted at an altitude of 10 meters over six corn farming areas located in the municipalities of Caarapó (MS) and Dourados (MS), Brazil. The UAV was a multirotor, model Phantom 4 Advanced, equipped with a 20-MP Sony camera (5472 × 3648 pixels).

In total, 1,583 images were collected during the weed-prone phenological stages V3, V4, and V5, of which 1,391 contained weeds and compose the WEED6C dataset.

Each image was annotated with object bounding boxes corresponding to the plant species present in the crop. The same image may contain multiple occurrences of the same or different species. Volunteer soybean plants were considered weeds because corn was the main crop.

The dataset contains six annotated classes:

- Bittercress (*Cardamine bonariensis*)
- Sourgrass (*Digitaria insularis*)
- Coconut (*Cocos nucifera*)
- Mastruz (*Dysphania ambrosioides*)
- Soybean (*Glycine max*)
- Johnsongrass (*Sorghum halepense*)

## Dataset Versions

Two versions of the WEED6C dataset are publicly available.

### WEED6C V1 — Original Version

WEED6C V1 is the original version of the dataset used in the experiments reported by Tetila et al. (2025).

This version is maintained to ensure reproducibility of the experiments and results reported in the original publication.

**Annotations:** 9,967 objects

**Download:**

http://evertontetila.ws.ufgd.edu.br/Datasets/WEED6C-Dataset.zip

### WEED6C V2 — Revised Version

WEED6C V2 contains the same images as the original WEED6C dataset, but its annotations were systematically reviewed and curated.

During the revision, the original annotations were systematically reviewed using the Computer Vision Annotation Tool (CVAT). Previously unlabeled instances were added, inconsistent annotations were removed, imprecise bounding boxes were geometrically corrected, and some class labels were reassigned.

The annotation review increased the total number of labeled objects from 9,967 in WEED6C V1 to 15,289 in WEED6C V2.

| Class | Species | V1 | V2 |
|---|---|---:|---:|
| Bittercress | *Cardamine bonariensis* | 1,541 | 3,807 |
| Sourgrass | *Digitaria insularis* | 1,454 | 1,737 |
| Coconut | *Cocos nucifera* | 719 | 1,061 |
| Mastruz | *Dysphania ambrosioides* | 2,598 | 3,658 |
| Soybean | *Glycine max* | 3,064 | 3,765 |
| Johnsongrass | *Sorghum halepense* | 591 | 1,261 |
| **Total** |  | **9,967** | **15,289** |

WEED6C V2 is recommended for new experiments, while WEED6C V1 remains publicly available for reproducing the experiments reported in the original publication.

**Download:**

https://evertontetila.ws.ufgd.edu.br/Datasets/WEED6CV2-Dataset.zip

## Citation

### WEED6C V1

If you use the original WEED6C dataset (V1), please cite:

TETILA, EVERTON CASTELÃO; WIRTI, GELSON; HIGA, GABRIEL TOSHIO HIROKAWA; DA COSTA, ANDERSON BESSA; AMORIM, WILLIAN PARAGUASSU; PISTORI, HEMERSON; BARBEDO, JAYME GARCIA ARNAL. Deep learning models for detection and recognition of weed species in corn crop. CROP PROTECTION, v. 195, p. 107237, 2025. DOI: https://doi.org/10.1016/j.cropro.2025.107237

### WEED6C V2

If you use WEED6C V2, please cite:

MARTINS, THIAGO MANTOVANI; TETILA, EVERTON CASTELÃO; BARBEDO, JAYME GARCIA ARNAL; ZHAO, LIANG; FELIPE, JOAQUIM CEZAR. Enhancing weed detection in corn crops through attention-based models and curated datasets. In: 17th International Conference on Precision Agriculture and 11th Brazilian Congress on Precision and Digital Agriculture, 2026, Porto Alegre. Proceedings. Monticello: International Society of Precision Agriculture, 2026. Unpaginated, online. In press.

WEED6C V2 is a revised version of the original dataset. Therefore, the original WEED6C publication should also be cited:

TETILA, EVERTON CASTELÃO; WIRTI, GELSON; HIGA, GABRIEL TOSHIO HIROKAWA; DA COSTA, ANDERSON BESSA; AMORIM, WILLIAN PARAGUASSU; PISTORI, HEMERSON; BARBEDO, JAYME GARCIA ARNAL. Deep learning models for detection and recognition of weed species in corn crop. CROP PROTECTION, v. 195, p. 107237, 2025. DOI: https://doi.org/10.1016/j.cropro.2025.107237
