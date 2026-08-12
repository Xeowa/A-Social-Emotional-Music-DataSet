# SEM Music Dataset: Social-Emotional Music Classification

[![Kaggle Dataset](https://img.shields.io/badge/Kaggle-View%20Dataset-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/xeowayeh/social-emotional-music)
[![Research Paper](https://img.shields.io/badge/DOI-10.1016%2Fj.mlwa.2025.100832-blue)](https://doi.org/10.1016/j.mlwa.2025.100832)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](LICENSE)

The **SEM Music Dataset** is an expert-annotated collection of 419 music tracks organized into three social-emotional learning (SEL) labels. It supports research and prototyping in music information retrieval, audio classification, and educational technology.

## Get the data

> ### [Download the SEM Music Dataset on Kaggle →](https://www.kaggle.com/datasets/xeowayeh/social-emotional-music)
>
> The audio files are hosted on Kaggle. This GitHub repository is the documentation, citation, and rights-information entry point.

## Research context

The dataset is associated with the peer-reviewed study:

> Y.-J. Lin et al., **“LSEL: A lightweight deep learning model for social-emotional classification of classical music,”** *Machine Learning with Applications*, vol. 23, article 100832, 2026. [https://doi.org/10.1016/j.mlwa.2025.100832](https://doi.org/10.1016/j.mlwa.2025.100832)

The study introduces LSEL, a lightweight model that classifies three higher-order SEL competencies using an expert-annotated SEM dataset. The public Kaggle release documented here contains **419 source tracks**; the paper reports **591 experimental samples** used in its model-evaluation pipeline. These figures refer to different stages of the research data and should not be treated as interchangeable inventory counts.

## Dataset overview

| Item | Value |
| --- | --- |
| Tracks in the public release | 419 WAV files |
| Approximate duration | 3.5 hours |
| Approximate download size | 2.5 GB |
| Reported sample rate | 44.1 kHz |
| Dataset version | 1.0 |
| Initial release | 2025 |

| Label | Tracks | Operational meaning used in this dataset |
| --- | ---: | --- |
| **Outlook** | 147 | Music selected to represent a positive or forward-looking emotional direction |
| **Problem-Solving** | 138 | Music selected to represent persistence, reflection, or working through difficulty |
| **Empathetic Perspective-Taking** | 134 | Music selected to represent emotional understanding or consideration of another perspective |

These labels are research-oriented organizational categories rather than clinical diagnoses or guarantees about an individual listener's response.

## Expert annotation

The music was professionally annotated by **Dr. Shan-Ken Chien (簡山根)**, Associate Professor and violinist at Chung Yuan Christian University. His expertise includes violin performance, chamber music, Baroque music, and music education.

- [Institutional profile](https://scholars.lib.cycu.edu.tw/cris/uuid/42a1ec37-b078-4639-aee1-fcab3da341d9)
- Research and annotation contact: [shanken@cycu.edu.tw](mailto:shanken@cycu.edu.tw)

## Intended uses

- Exploratory audio-feature analysis and visualization
- Baseline music-label classification experiments
- Reproduction or extension of SEL-oriented music-classification research
- Prototyping music recommendation and educational interfaces

Users should independently validate whether the labels, sample composition, and preprocessing are suitable for their research question. Please document any excluded, relabeled, segmented, augmented, or transformed files.

## Citation

When using the dataset, cite both the accessed dataset version and the related paper where appropriate.

**Dataset**

> Yeh, K.-K. (2025). *SEM Music Dataset: A Dataset for Social-Emotional Music Classification* (Version 1.0) [Data set]. Kaggle. https://www.kaggle.com/datasets/xeowayeh/social-emotional-music

**Related paper**

> Lin, Y.-J., Chou, Y.-C., Chien, S.-K., Chao, P.-C., Yeh, K.-K., Peng, Y.-C., Tsao, C.-H., Chen, C.-Y., Chen, S.-L., Li, K.-C., & Tu, W.-C. (2026). LSEL: A lightweight deep learning model for social-emotional classification of classical music. *Machine Learning with Applications, 23*, 100832. https://doi.org/10.1016/j.mlwa.2025.100832

Machine-readable metadata is available in [`CITATION.cff`](CITATION.cff).

## Rights and limitations

Repository documentation, original metadata, and original annotations authored for this dataset are licensed under [CC BY-NC 4.0](LICENSE), unless a file states otherwise.

Underlying musical compositions, performances, and sound recordings may carry separate rights and are not automatically covered by the repository license. Review [`RIGHTS.md`](RIGHTS.md) and the applicable source permissions before redistributing audio.

Additional limitations:

- Emotional interpretation may vary by listener, culture, and context.
- The collection is not presented as a clinically validated assessment instrument.
- The labels should not be used to infer mental-health status or other sensitive attributes about individuals.

## Contact

- Music annotation and related research: **Dr. Shan-Ken Chien** — [shanken@cycu.edu.tw](mailto:shanken@cycu.edu.tw)
- Repository maintenance and reproducibility notes: open a [GitHub Issue](https://github.com/Xeowa/A-Social-Emotional-Music-DataSet/issues)

## Version history

- **1.0 (2025):** Initial public dataset release.
