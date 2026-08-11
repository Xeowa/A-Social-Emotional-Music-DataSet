# SEM Music Dataset

The **SEM Music Dataset** is a curated collection of 419 music tracks organized into three project-defined social-emotional labels. It is intended for exploratory work in music information retrieval, audio classification, and educational technology.

> **Data access:** The dataset files are hosted on [Kaggle](https://www.kaggle.com/datasets/xeowayeh/social-emotional-music). This GitHub repository is the documentation and citation entry point.

## Dataset overview

| Item | Value |
| --- | --- |
| Tracks | 419 WAV files |
| Approximate duration | 3.5 hours |
| Approximate download size | 2.5 GB |
| Reported sample rate | 44.1 kHz |
| Version | 1.0 |
| Published | 2025 |

The three labels and their reported item counts are:

| Label | Tracks | Operational meaning used in this dataset |
| --- | ---: | --- |
| Outlook | 147 | Music selected to represent a positive or forward-looking emotional direction |
| Problem-Solving | 138 | Music selected to represent persistence, reflection, or working through difficulty |
| Empathetic Perspective-Taking | 134 | Music selected to represent emotional understanding or consideration of another perspective |

These labels are project-specific organizational categories. They are not clinical diagnoses, validated psychological measurements, or claims about a listener's response.

## Intended uses

- Exploratory audio-feature analysis and visualization
- Baseline music-label classification experiments
- Prototyping music recommendation or educational interfaces
- Reproducible coursework and research-method demonstrations

Users should independently validate whether the labels and sample composition are suitable for their research question. The dataset does not establish therapeutic effectiveness, learning outcomes, or universal emotional interpretations.

## Recommended workflow

1. Download the data from the Kaggle page.
2. Record the dataset version and access date in the experiment log.
3. Inspect file counts, audio properties, and label balance before training.
4. Use stratified evaluation where appropriate and report per-label metrics.
5. Document any excluded, relabeled, or transformed files.

## Citation

If you use the dataset, cite the version you accessed:

> Xeowa. (2025). *SEM Music Dataset: A Dataset for Social-Emotional Music Classification* (Version 1.0) [Data set]. Kaggle. https://www.kaggle.com/datasets/xeowayeh/social-emotional-music

Machine-readable citation metadata is available in [`CITATION.cff`](CITATION.cff).

## Authorship and maintenance

**Xeowa** is the dataset author and repository maintainer. Questions, corrections, and reproducibility notes may be submitted through GitHub Issues.

## Rights and license scope

The repository documentation, original metadata, and original annotations authored by Xeowa are licensed under [CC BY-NC 4.0](LICENSE), unless a file states otherwise.

Underlying musical compositions, performances, and sound recordings are **not automatically covered** by that repository license. They retain the rights and conditions associated with their original sources. Before redistributing audio or using it beyond the Kaggle access terms, users must review the applicable per-track and platform permissions.

See [`RIGHTS.md`](RIGHTS.md) for the material-by-material scope. This repository's license notice does not transfer ownership of third-party works or override any existing rights.

## Limitations

- Emotional interpretation is subjective and may vary by listener, culture, and context.
- The category counts and technical inventory should be checked against the downloaded version before publication of derived results.
- The collection is not presented as a clinically validated instrument.
- The labels should not be used to infer mental-health status or other sensitive attributes about individuals.

## Version history

- **1.0 (2025):** Initial public dataset release.
