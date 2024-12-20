# Deep Superpixel Generation and Clustering for Weakly Supervised Segmentation of Brain Tumors in MR Images
Code for training and running weakly supervised brain tumor segmentation models using simultaneous superpixel generation and clustering.

![Flowchart](flowchart.jpg)

Please see [Superpixel Generation and Clustering for Weakly Supervised Brain Tumor Segmentation in MR Images](https://doi.org/10.1186/s12880-024-01523-x) for details.

If you use this code, please cite:
```
﻿@article{yoo2024superpixel,
author={Yoo, Jay J.
and Namdar, Khashayar
and Khalvati, Farzad},
title={Deep superpixel generation and clustering for weakly supervised segmentation of brain tumors in MR images},
journal={BMC Medical Imaging},
year={2024},
month={Dec},
day={18},
volume={24},
number={1},
pages={335},
abstract={Training machine learning models to segment tumors and other anomalies in medical images is an important step for developing diagnostic tools but generally requires manually annotated ground truth segmentations, which necessitates significant time and resources. We aim to develop a pipeline that can be trained using readily accessible binary image-level classification labels, to effectively segment regions of interest without requiring ground truth annotations.},
issn={1471-2342},
doi={10.1186/s12880-024-01523-x},
url={https://doi.org/10.1186/s12880-024-01523-x}
}
```

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JayJaewonYoo/BrainTumorWSS_Superpixels/blob/main/training_inference_example.ipynb) See the linked notebook for details on initializing, training, and performing inference using the models. 
