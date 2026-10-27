# Datasets Used in HullSynergy

This document provides the source pages and download links for the three existing datasets used in HullSynergy: HRSC2016, FGSD2021, and DOSR. The datasets were created by their respective authors. This repository provides access information and does not host the original images or annotations.

## Download overview

| Dataset  | Source page                                                  | Download                                                     | Access code                                                  |
| -------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| HRSC2016 | [IEEE DataPort](https://ieee-dataport.org/documents/hrsc2016) | Download `HRSC2016_dataset.zip` from the linked DataPort page | Not applicable; DataPort authentication and access requirements apply |
| FGSD2021 | [Author repository: CHPDet](https://github.com/zf020114/CHPDet) | [Baidu Netdisk](https://pan.baidu.com/s/1q1YQsFAR6nvWIVoa6eo85w?pwd=nudt) | `nudt`                                                       |
| DOSR     | [Author repository: DOSR](https://github.com/yaqihan-9898/DOSR) | [Google Drive](https://drive.google.com/file/d/1X0vKWP7TlGK_4kiVVGMVSUbEhZoFT-l3/view?usp=sharing) or [Baidu Netdisk](https://pan.baidu.com/s/1I7N0I_y2en2_PyYhMzuScg) | Baidu Netdisk: `1596`                                        |

The FGSD2021 and DOSR download links and access codes are listed in their authors' repositories. If a link changes, consult the corresponding source page for updates. Cloud storage services may require sign-in. Download completion has not been tested here.

## HRSC2016

HRSC2016 is a high-resolution optical remote sensing dataset for ship detection and recognition. It contains 1,061 images and includes oriented bounding box annotations. HullSynergy uses the single-class ship detection setting.

- Dataset title on IEEE DataPort: **HRSC2016**.
- Repository: **IEEE DataPort**.
- Dataset DOI for the DataPort entry linked above: [10.21227/km4k-0385](https://doi.org/10.21227/km4k-0385).
- Dataset paper: Z. Liu, L. Yuan, L. Weng, and Y. Yang, “A High Resolution Optical Satellite Image Dataset for Ship Recognition and Some New Baselines,” ICPRAM, 2017.
- Paper DOI: [10.5220/0006120603240331](https://doi.org/10.5220/0006120603240331).

The DataPort dataset DOI identifies the specific repository entry above; the paper DOI identifies the publication introducing the dataset.

## FGSD2021

FGSD2021 supports multiclass, arbitrary-oriented ship detection at a fixed ground sample distance. The authors distribute the dataset through the CHPDet repository, which links to the Baidu Netdisk download listed above.

- Dataset title: **FGSD2021**.
- Source repository: **GitHub — zf020114/CHPDet**.
- Independent dataset DOI: not provided on the linked author repository.
- Dataset paper: F. Zhang, X. Wang, S. Zhou, Y. Wang, and Y. Hou, “Arbitrary-Oriented Ship Detection Through Center-Head Point Extraction,” IEEE Transactions on Geoscience and Remote Sensing, vol. 60, 2022.
- Paper DOI: [10.1109/TGRS.2021.3120411](https://doi.org/10.1109/TGRS.2021.3120411).

## DOSR

The **Dataset for Oriented Ship Recognition (DOSR)** supports fine-grained oriented ship recognition. It contains 1,066 optical remote sensing images and 6,127 ship instances across 20 classes. The authors provide five-parameter and eight-parameter bounding box annotations.

- Dataset title: **Dataset for Oriented Ship Recognition (DOSR)**.
- Source repository: **GitHub — yaqihan-9898/DOSR**.
- Independent dataset DOI: not provided on the linked author repository.
- Dataset paper: Y. Han, X. Yang, T. Pu, and Z. Peng, “Fine-Grained Recognition for Oriented Ship Against Complex Scenes in Optical Remote Sensing Images,” IEEE Transactions on Geoscience and Remote Sensing, vol. 60, 2022.
- Paper DOI: [10.1109/TGRS.2021.3123666](https://doi.org/10.1109/TGRS.2021.3123666).

## Evaluation protocol in HullSynergy

The HullSynergy manuscript uses local training, validation, and test partitions in an 8:1:1 ratio and ProbIoU-based matching. These experimental settings should be distinguished from the original datasets' default splits and from evaluation based on polygonal rotated IoU. The download links above provide access to the source datasets; this document does not contain the local split manifests or preprocessed data.

## Attribution and use

Please cite the original dataset publications and follow the access and usage conditions specified by the dataset authors and hosting services. The links collected here do not grant additional redistribution rights.

Source pages reviewed on **October 27, 2026**.
