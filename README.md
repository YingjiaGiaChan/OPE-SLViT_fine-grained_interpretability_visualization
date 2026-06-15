# OPE-SLViT: Interpretable Pediatric Brain Age Estimation From Structural MRI

This repository is associated with the manuscript:

**An Interpretable Vision Transformer Identifies a Reproducible Posterior Temporal-Occipital MRI Pattern Associated With Pediatric Brain Age**

## Repository Status

The full codebase is currently not publicly available. The source code and cleaned reproduction package supporting the reported analyses will be released in this repository upon manuscript acceptance.

Third-party participant-level MRI data are not included in this repository. Users should obtain the original datasets from their respective repositories and comply with all applicable data-use agreements.

## Overview

OPE-SLViT is an interpretable Vision Transformer framework for pediatric brain age estimation from structural MRI. The method combines coverage-aware multi-scale patch sampling, a single-layer attention pathway, and query-key orthogonality regularization to preserve complementary anatomical evidence. During inference, token-level evidence is reprojected into voxel space for saliency evaluation and region-of-interest analysis.

In the associated study, OPE-SLViT was evaluated on 2,536 pediatric structural MRI scans from ABIDE I, ABIDE II, Calgary, NIHPD, and PING. The model achieved competitive brain age prediction and identified a reproducible posterior temporal-occipital candidate pattern, with the posterior middle temporal gyrus and occipital pole forming a cross-protocol core across five-fold cross-validation and leave-one-dataset-out validation.

## Planned Release

Once released, this repository will include:

1. Implementation of the OPE-SLViT model
2. Coverage-aware multi-scale patch sampling modules
3. Query-key orthogonality regularization components
4. Training and evaluation scripts for pediatric brain age estimation
5. Voxel-level saliency reprojection and visualization code
6. ROI-level saliency analysis and reproducibility evaluation scripts
7. Example configuration files and documentation for reproducing the main analyses

## Data Availability

The MRI data analyzed in the manuscript were obtained from third-party repositories, including ABIDE I, ABIDE II, Calgary, NIHPD, and PING. The authors did not generate new participant-level MRI data and cannot redistribute source MRI data whose repository terms prohibit redistribution.

This repository will provide code and analysis scripts only. Users are responsible for obtaining access to the required datasets through the original data providers and for following all relevant data-use conditions.

## Citation

Citation information will be added after the manuscript is accepted and bibliographic details become available.

## Contact

For questions about the repository or the associated manuscript, please contact the corresponding authors listed in the manuscript.

