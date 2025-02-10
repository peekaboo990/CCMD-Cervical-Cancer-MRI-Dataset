# CCMD-Cervical-Cancer-MRI-Dataset: An Open MRI Dataset for Cervical Cancer with Tumor Segmentation Using nnU-Net

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
| Patient Cohort    | 151 female patients (Age 28-65)             |
| Scan Parameters   | 1.5T/3T scanners; Sagittal views            |
| Annotation Scope  | Tumor boundaries |

## Data Structure
```bash

root/

├── patient_1/

│ ├── volumes/

│ │ ├── t2w.nrrd

│ │ └── contrast-enhanced.nrrd

│ └── annotations/

│ ├── tumor_mask.nrrd

├── patient_2/

└── ...

```


## Download

The dataset is available under restricted access for research purposes.  
[**Download Link**](https://pan.baidu.com/s/1hMSEFqa_kwnDBj5q_zIFHA)  

**To request access password:**  
1. Send email to [n13677994752@163.com](mailto:n13677994752@163.com)  
2. Include your institutional affiliation and research purpose  
3. Allow 3-5 working days for approval processing

## Usage Guidelines

1. Clinical use requires consultation with medical experts
2. Commercial use prohibited without written permission
3. Cite this dataset in derivative works (see citation below)
4. Annotations should be validated by qualified radiologists

## Citation

Please cite this dataset if used in your research:
```bibtex
@misc{CervicalCancerMRI2025,
  title = {An Open MRI Dataset for Cervical Cancer with Tumor Segmentation Using nnU-Net},
  author = {
    Genyun Liu and 
    Yi Tang and 
    Lin Guo and 
    Liwei Zhang and 
    Qisong Zheng and 
    Hui Hui and 
    Li Cai and 
    Yun Zhou
  },
  year = {2025},
  url = {https://github.com/peekaboo990/CCMD-Cervical-Cancer-MRI-Dataset},
}
