# CCMD-Cervical-Cancer-MRI-Dataset：An Open MRI Dataset for Cervical Cancer with Tumor Segmentation Using nnU-Net

## Dataset Overview

This dataset contains **T2-weighted MRI (T2WI)** scans of pelvic regions with corresponding **physician-annotated ROI (Region of Interest)** images for cervical cancer analysis. The collection aims to support research in:

- Medical image analysis
- Tumor segmentation
- Computer-aided diagnosis (CAD)
- Deep learning applications
- Radiomics research

## Dataset Details

| Category          | Description                                  |
|-------------------|----------------------------------------------|
| Modality          | T2-weighted MRI (T2WI)                      |
| Annotation Type   | Expert-labeled ROI masks                    |
| Image Format      | DICOM (Original scans) + PNG (Annotations)  |
| Patient Cohort    | 151female patients (Age 28-65)             |
| Scan Parameters   | 1.5T/3T scanners,Sagittal views      |
| Annotation Scope  | Tumor boundaries, lymph nodes, organs-at-risk |

## Data Structure
root/
├── patient_1/
│ ├── DICOM/
│ │ ├── series_1/
│ │ └── series_2/
│ └── Annotations/
│ ├── tumor_mask.png
├── patient_2/
└── ...

## Download

The dataset is available via Baidu Cloud:

[![Baidu Pan](https://pan.baidu.com/your-link-here](https://pan.baidu.com/s/1Kdw-Wznm4iB65WGp1ATfCQ?pwd=ri77))   
**Extract Code:** ri77 

## Usage Guidelines

1. Clinical use requires consultation with medical experts
2. Commercial use prohibited without written permission
3. Cite this dataset in derivative works (see citation below)
4. Annotations should be validated by qualified radiologists

## Citation

Please cite this dataset if used in your research:
```bibtex
@misc{CervicalCancerMRI2023,
  title = {Cervical Cancer Pelvic MRI Dataset},
  author = {Your Institution/Name},
  year = {2023},
  url = {https://github.com/your-repo},
  note = {Open dataset containing T2WI scans with expert annotations}
}
