# Leveraging Feature Alignment in Grassmannian Manifold for Multi-Output Regression Tasks

This repository contains the official implementation of our paper published in **IEEE Transactions on Image Processing (2026)**.

**Paper Title:** Leveraging Feature Alignment in Grassmannian Manifold for Multi-Output Regression Tasks  
**DOI:** [10.1109/TIP.2026.3695336](https://doi.org/10.1109/TIP.2026.3695336)  
**IEEE Link:** [Read on IEEE Xplore](https://ieeexplore.ieee.org/document/11536837)

## Overview

This work proposes a novel domain adaptation regression method that leverages **Grassmannian manifold** for robust feature alignment while preserving the structural integrity of the data. Unlike traditional methods that rely on Euclidean space alignments, our **Grassmannian Manifold Distance (GMD)** approach maps features onto the Grassmann manifold to achieve more accurate and stable multi-output regression across domains.

## Method Summary

Our proposed method (GMD) aligns source and target domains by:
- Projecting features onto the Grassmannian manifold
- Computing geodesic distances to align subspaces
- Preserving discriminative information during alignment
- Optimizing with a regression loss on the aligned representations

For a detailed information with existing domain adaptation methods (**DARE-GRAM, RSD, PnP-GA, CORAL, DANN, DAN, MCD, AFN, DSAN, BNM, BSP, SSRT, **etc.), please refer to **Table I** in the original paper. A summary table is available in the manuscript.

## Datasets

We evaluate our method on several benchmark datasets:

### Public Datasets
- [**Office-31**](https://opendatalab.com/OpenDataLab/Office-31) - Standard domain adaptation benchmark for object recognition
- [**Disentanglement Dataset**](https://github.com/rr-learning/disentanglement_dataset) - For multi-output regression tasks

### Restricted Dataset
- **Plants *Arabidopsis thaliana*** - This dataset requires explicit permission from the original authors. Please contact them directly for access.

## Code Acknowledgments

Our implementation references and builds upon the following open-source repositories. We sincerely thank all the authors for making their code available:

| Repository | Description |
|------------|-------------|
| [transferlearning](https://github.com/jindongwang/transferlearning) | Comprehensive transfer learning library |
| [PnP-GA](https://github.com/DreamtaleCore/PnP-GA) | Plug-and-Play Generalization Adapters |
| [Domain-Adaptation-Regression](https://github.com/thuml/Domain-Adaptation-Regression) | Regression-specific domain adaptation methods |
| [DARE-GRAM](https://github.com/ismailnejjar/DARE-GRAM) | DARE-GRAM for domain adaptation regression |

## Citation

If you find this work useful for your research, please cite our paper:

```bibtex
@ARTICLE{11536837,
  author={Kong, Lingping and Zdražil, Jan and De Diego, Nuria and Ignacio Jasso Robles, Francisco and Snášel, Václav and Das, Swagatam and Pan, Jeng-Shyang},
  journal={IEEE Transactions on Image Processing}, 
  title={Leveraging Feature Alignment in Grassmannian Manifold for Multi-Output Regression Tasks}, 
  year={2026},
  volume={35},
  number={},
  pages={5804-5817},
  doi={10.1109/TIP.2026.3695336}
}
## updating-
