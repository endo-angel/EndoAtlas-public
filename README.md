# EndoAtlas-public
Public Dataset Description for Multimodal Gastrointestinal Endoscopic Medical Images
Dataset Overview

This dataset is a multimodal gastrointestinal endoscopic medical image dataset, including three types of images: white-light endoscopy, capsule endoscopy, and endoscopic ultrasound. The dataset covers digestive organs such as the stomach, colorectum, small intestine, and pancreas, and includes neoplastic lesions, inflammatory lesions, polypoid lesions, vascular lesions, and other related contents.This dataset is intended to provide data support for gastrointestinal endoscopic image recognition, lesion detection, lesion segmentation, ultrasound endoscopy station recognition, artificial intelligence-assisted diagnosis, medical image algorithm validation, and teaching research.

Dataset Composition

The dataset is organized according to endoscopic modality, examination site, lesion category, and task type. The detailed composition is as follows.

1. White-Light Endoscopy Images

White-light endoscopy images include gastric images and colorectal images.

1.1 Gastric White-Light Endoscopy Images

The gastric white-light endoscopy subset contains 75 images, including:

| Category | Number of Images |
|---|---:|
| Advanced gastric cancer | 5 |
| High-grade intraepithelial neoplasia | 10 |
| Low-grade intraepithelial neoplasia | 15 |
| Atrophic gastritis | 25 |
| Intestinal metaplasia | 20 |

1.2 Colorectal White-Light Endoscopy Images

The colorectal white-light endoscopy subset is a polyp dataset, including Detection and segmentation tasks. Original images and labled images are provided.

| Task Type | Data Type | Number of Images |
|---|---|---:|
| Detection | Original images | 100 |
| Detection | Labled images | 100 |
| Segmentation | Original images | 100 |
| Segmentation | Labled images | 100 |

2. Capsule Endoscopy Images

The capsule endoscopy subset contains 80 images, all from the small intestine, including protruding lesions, erosions/ulcers, polyps/hyperplasia, and vascular lesions.

| Category | Number of Images |
|---|---:|
| Protruding lesion | 20 |
| Erosion/ulcer | 30 |
| Polyp/hyperplasia | 10 |
| Vascular lesion | 20 |

3. Endoscopic Ultrasound Images

The endoscopic ultrasound images are organized according to standard scanning stations, with a total of 40 images. Each station contains 5 images.

| Station | Number of Images |
|---|---:|
| Liver window | 5 |
| Abdominal aorta | 5 |
| Pancreatic body | 5 |
| Pancreatic tail | 5 |
| Confluence triangle | 5 |
| Pancreatic head through the gastric cavity | 5 |
| Duodenal bulb station | 5 |
| Gallbladder station | 5 |

Dataset Size Summary

| Endoscopic Modality | Site/Direction | Number of Images |
|---|---|---:|
| White-light endoscopy | Stomach | 75 |
| White-light endoscopy | Colorectal polyps | 400 |
| Capsule endoscopy | Small intestine | 80 |
| Endoscopic ultrasound | Standard scanning stations | 40 |
| Total | — | 595 |

Dataset Features

1. Coverage of Multimodal Endoscopic Images

The dataset includes white-light endoscopy, capsule endoscopy, and endoscopic ultrasound images, supporting image analysis research across different endoscopic imaging modalities.

2. Coverage of Multiple Digestive Organs

The dataset covers multiple digestive organs, including the stomach, colorectum, small intestine, and pancreas, providing diversity in image types.

3. Support for Detection, Segmentation, and Recognition Tasks

The colorectal polyp subset includes detection and segmentation tasks, with original images and annotated images provided. The endoscopic ultrasound subset is organized according to standard scanning stations and can be used for endoscopic ultrasound station recognition and teaching research.

4. Support for Model Training

The dataset includes multiple lesion categories, such as gastric cancer, intraepithelial neoplasia, atrophic gastritis, intestinal metaplasia, small intestinal protruding lesions, erosions/ulcers, polyps/hyperplasia, and vascular lesions. It can be used for training and validating classification models.

5. Suitability for Medical Artificial Intelligence Research

The dataset can be used for gastrointestinal endoscopic image classification, lesion recognition, lesion segmentation, endoscopic ultrasound station recognition, assisted diagnostic model development, and medical teaching.

Potential Applications

This dataset can be used for, but is not limited to, the following research directions:

- Classification and recognition of gastrointestinal endoscopic images;
- Assisted diagnosis research for gastric lesions, colorectal polyps, and small intestinal lesions;
- Detection and lesion segmentation research for colorectal polyp images;
- Recognition of standard scanning stations in endoscopic ultrasound;
- Development of multimodal medical image analysis algorithms;
- Training, validation, and performance evaluation of deep learning models;
- Gastrointestinal endoscopy teaching and research demonstration.

Data Usage Statement

This dataset is intended for non-commercial purposes, including scientific research, teaching, and algorithm validation. Users should comply with relevant requirements regarding medical ethics, data security, and privacy protection when using the dataset. Necessary data organization and de-identification should be completed before release to ensure that no identifiable personal information, such as patient names, identification numbers, or examination dates, is included.

If this dataset is used in research or related publications, users are encouraged to acknowledge the data source in their papers, reports, or project descriptions.
