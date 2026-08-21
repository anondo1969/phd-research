# PhD Research Archive

This repository is an index of the code, papers, slides, posters, videos, and demos from my PhD research at Stockholm University (2018–2024), with my earlier Master's thesis included at the end.

My thesis points readers to my GitHub profile for research code. I now use that profile mainly for current engineering work, so this archive keeps the research easy to find without taking over the pinned section.

The original code repositories stay where they are. This repository only gives them one stable starting point.

## PhD thesis

**Advancing Clinical Decision Support Using Machine Learning & the Internet of Medical Things: Enhancing COVID-19 & Early Sepsis Detection**  
Department of Computer and Systems Sciences, Stockholm University, 2024.

[![Thesis](https://img.shields.io/badge/PhD-Thesis-555555?style=flat-square)](https://su.diva-portal.org/smash/record.jsf?pid=diva2%3A1833062)
[![Defence Slides](https://img.shields.io/badge/Defence-Slides-0078D4?style=flat-square)](https://mahbub.blogs.dsv.su.se/files/2025/02/defence_presentation_slides.pdf)
[![Defence Video](https://img.shields.io/badge/Defence-Video-B42318?style=flat-square)](https://mahbub.blogs.dsv.su.se/files/2025/09/PhD_defence_28-03-2024_Mahbub_Ul_Alam.mp4)
[![Publications](https://img.shields.io/badge/All-Publications-2E7D32?style=flat-square)](https://mahbub.blogs.dsv.su.se/publications/)
[![Presentation Resources](https://img.shields.io/badge/Slides%20%7C%20Posters%20%7C%20Videos-Resources-A142F4?style=flat-square)](https://mahbub.blogs.dsv.su.se/publication-presentation-slides/)

## Media gallery

The cards below are clickable. PDFs open as full slide decks or posters; videos open in the browser. GitHub does not reliably preview external PDFs and videos inside a README, so I use linked visual cards instead.

<table>
<tr>
<td width="50%" align="center">
<a href="https://mahbub.blogs.dsv.su.se/files/2025/02/defence_presentation_slides.pdf"><img src="assets/media/phd-defence.svg" alt="PhD public defence slides" width="100%"></a><br>
<a href="https://mahbub.blogs.dsv.su.se/files/2025/09/PhD_defence_28-03-2024_Mahbub_Ul_Alam.mp4">▶ Watch the PhD defence</a>
</td>
<td width="50%" align="center">
<a href="https://mahbub.blogs.dsv.su.se/files/2022/05/poster_Mahbub_Ul_Alam.pdf"><img src="assets/media/paper-i-poster.svg" alt="Paper I poster" width="100%"></a><br>
<a href="https://mahbub.blogs.dsv.su.se/files/2022/05/poster_Mahbub_Ul_Alam.pdf">Open poster PDF</a>
</td>
</tr>
<tr>
<td width="50%" align="center">
<a href="https://github.com/anondo1969/thremaltimodal-covidetector/raw/main/slides_and_results/presentation_slides_v3.pdf"><img src="assets/media/paper-ii-slides.svg" alt="Paper II presentation slides" width="100%"></a><br>
<a href="https://github.com/anondo1969/thremaltimodal-covidetector/raw/main/slides_and_results/presentation_slides_v3.pdf">Open Paper II slides</a>
</td>
<td width="50%" align="center">
<a href="https://mahbub.blogs.dsv.su.se/files/2023/01/FedSepsis_Mahbub_Ul_Alam.pdf"><img src="assets/media/fedsepsis-slides.svg" alt="FedSepsis presentation slides" width="100%"></a><br>
<a href="https://mahbub.blogs.dsv.su.se/files/2023/01/FedSepsis_Mahbub_Ul_Alam.pdf">Open FedSepsis slides</a>
</td>
</tr>
<tr>
<td width="50%" align="center">
<a href="https://mahbub.blogs.dsv.su.se/files/2022/07/presentation_slides.pdf"><img src="assets/media/paper-v-media.svg" alt="Paper V slides and video" width="100%"></a><br>
<a href="https://mahbub.blogs.dsv.su.se/files/2022/07/presentation_video_extended.mp4">▶ Watch the extended presentation</a>
</td>
<td width="50%" align="center">
<a href="#other-presentations-from-the-phd-years"><img src="assets/media/other-talks.svg" alt="Other presentations from the PhD years" width="100%"></a><br>
<a href="#other-presentations-from-the-phd-years">See the other talks</a>
</td>
</tr>
</table>

## Thesis papers at a glance

| Paper | Main topic | Code |
|---|---|---|
| I | Federated and semi-supervised learning for COVID-19 detection and lung segmentation | [`FedSemiCovidDetector`](https://github.com/anondo1969/FedSemiCovidDetector) |
| II | Multimodal COVID-19 detection from thermal images and tabular data | [`thremaltimodal-covidetector`](https://github.com/anondo1969/thremaltimodal-covidetector) |
| III | IoMT architecture and deep learning for early sepsis detection | [`FedSepsis/single_server_setting`](https://github.com/anondo1969/FedSepsis/tree/main/FedSepsis_codes/single_server_setting) |
| IV | Federated multimodal early sepsis detection on edge devices | [`FedSepsis`](https://github.com/anondo1969/FedSepsis) |
| V | LRP and Grad-CAM for interpreting chest X-ray models | [`lrp-grad_cam-chexpert`](https://github.com/anondo1969/lrp-grad_cam-chexpert) |
| VI | SHAMSUL: comparing several local interpretability methods for chest radiography | [`SHAMSUL`](https://github.com/anondo1969/SHAMSUL) |

---

## Paper I — Federated semi-supervised COVID-19 detection and lung segmentation

**Federated Semi-Supervised Multi-Task Learning to Detect COVID-19 and Lungs Segmentation Marking Using Chest Radiography Images and Raspberry Pi Devices: An Internet of Medical Things Application**

This project studies COVID-19 detection and lung segmentation from chest X-rays when labelled data are limited and patient data cannot simply be collected in one place. It combines federated learning, semi-supervised learning, transfer learning, and multi-task learning, and tests the setup on Raspberry Pi devices.

[![Code](https://img.shields.io/badge/GitHub-Code-181717?style=flat-square&logo=github)](https://github.com/anondo1969/FedSemiCovidDetector)
[![Paper](https://img.shields.io/badge/DOI-Paper-B31B1B?style=flat-square)](https://doi.org/10.3390/s21155025)
[![Poster](https://img.shields.io/badge/Poster-PDF-0078D4?style=flat-square)](https://mahbub.blogs.dsv.su.se/files/2022/05/poster_Mahbub_Ul_Alam.pdf)

**Main themes:** federated learning · semi-supervised learning · multi-task learning · chest X-ray · Raspberry Pi · IoMT

---

## Paper II — Multimodal COVID-19 detection with thermal and tabular data

**COVID-19 detection from thermal image and tabular medical data utilizing multi-modal machine learning**

This project asks whether thermal images add useful information when combined with tabular medical data. It compares single-modality and multimodal models and studies which combination gives the best COVID-19 detection performance.

[![Code](https://img.shields.io/badge/GitHub-Code-181717?style=flat-square&logo=github)](https://github.com/anondo1969/thremaltimodal-covidetector)
[![Paper](https://img.shields.io/badge/DOI-Paper-B31B1B?style=flat-square)](https://doi.org/10.1109/CBMS58004.2023.00294)
[![Slides](https://img.shields.io/badge/Slides-PDF-0078D4?style=flat-square)](https://github.com/anondo1969/thremaltimodal-covidetector/raw/main/slides_and_results/presentation_slides_v3.pdf)

**Main themes:** multimodal learning · thermal imaging · tabular data · machine learning · COVID-19

---

## Paper III — IoMT architecture for early sepsis detection

**Cognitive Internet of Medical Things Architecture for Decision Support Tool to Detect Early Sepsis Using Deep Learning**

This work describes an IoMT architecture for early sepsis detection from electronic health records. The main problem is practical: clinical data are sparse, heterogeneous, and spread across systems. The project connects data preparation, model inference, and decision-support components into one architecture.

The implementation for this paper is kept inside the `FedSepsis` repository rather than in a separate repository.

[![Code](https://img.shields.io/badge/GitHub-Single--server%20code-181717?style=flat-square&logo=github)](https://github.com/anondo1969/FedSepsis/tree/main/FedSepsis_codes/single_server_setting)
[![Numeric pipeline](https://img.shields.io/badge/GitHub-Numeric%20pipeline-181717?style=flat-square&logo=github)](https://github.com/anondo1969/FedSepsis/tree/main/FedSepsis_codes/single_server_setting/sepsis_prediction/1_numeric)
[![Paper](https://img.shields.io/badge/DOI-Paper-B31B1B?style=flat-square)](https://doi.org/10.1007/978-3-030-72379-8_18)

**Main themes:** sepsis · electronic health records · data pipelines · deep learning · heterogeneous medical data · IoMT

---

## Paper IV — FedSepsis

**FedSepsis: A Federated Multi-Modal Deep Learning-Based Internet of Medical Things Application for Early Detection of Sepsis from Electronic Health Records Using Raspberry Pi and Jetson Nano Devices**

FedSepsis combines structured EHR data and clinical text for early sepsis prediction. It uses federated learning for distributed training, ClinicalBERT for text features, missing-data handling, and experiments on Raspberry Pi and Jetson Nano devices. The project also records system behaviour such as CPU, memory, temperature, disk use, and network traffic.

[![Code](https://img.shields.io/badge/GitHub-Code-181717?style=flat-square&logo=github)](https://github.com/anondo1969/FedSepsis)
[![Paper](https://img.shields.io/badge/DOI-Paper-B31B1B?style=flat-square)](https://doi.org/10.3390/s23020970)
[![Slides](https://img.shields.io/badge/Slides-PDF-0078D4?style=flat-square)](https://mahbub.blogs.dsv.su.se/files/2023/01/FedSepsis_Mahbub_Ul_Alam.pdf)

**Main themes:** federated learning · multimodal EHR · ClinicalBERT · missing data · Raspberry Pi · Jetson Nano · edge computing · sepsis

---

## Paper V — LRP and Grad-CAM for chest X-ray interpretation

**Exploring LRP and Grad-CAM visualization to interpret multi-label-multi-class pathology prediction using chest radiography**

This project compares Layer-wise Relevance Propagation (LRP) and Grad-CAM for explaining multi-label chest X-ray predictions. LRP gives detailed relevance maps, while Grad-CAM gives broader regions of attention. The paper received the Best Student Paper Award at IEEE CBMS 2022.

[![Code](https://img.shields.io/badge/GitHub-Code-181717?style=flat-square&logo=github)](https://github.com/anondo1969/lrp-grad_cam-chexpert)
[![Paper](https://img.shields.io/badge/DOI-Paper-B31B1B?style=flat-square)](https://doi.org/10.1109/CBMS55023.2022.00052)
[![Slides](https://img.shields.io/badge/Slides-PDF-0078D4?style=flat-square)](https://mahbub.blogs.dsv.su.se/files/2022/07/presentation_slides.pdf)
[![Video](https://img.shields.io/badge/Presentation-Video-B42318?style=flat-square)](https://mahbub.blogs.dsv.su.se/files/2022/07/presentation_video_extended.mp4)

**Main themes:** explainable AI · LRP · Grad-CAM · CheXpert · chest X-ray · multi-label classification

---

## Paper VI — SHAMSUL

**SHAMSUL: Systematic Holistic Analysis to investigate Medical Significance Utilizing Local interpretability methods in deep learning for chest radiography pathology prediction**

SHAMSUL compares Grad-CAM, LRP, LIME, and SHAP for explaining chest X-ray pathology predictions. It evaluates the explanations in several ways, including comparison with expert annotations. A public demo lets people explore the methods without setting up the research environment.

[![Code](https://img.shields.io/badge/GitHub-Code-181717?style=flat-square&logo=github)](https://github.com/anondo1969/SHAMSUL)
[![Paper](https://img.shields.io/badge/DOI-Paper-B31B1B?style=flat-square)](https://doi.org/10.5617/nmi.10471)
[![Paper PDF](https://img.shields.io/badge/Paper-PDF-0078D4?style=flat-square)](https://github.com/anondo1969/SHAMSUL/blob/main/SHAMSUL.pdf)
[![Demo](https://img.shields.io/badge/Live-Demo-2E7D32?style=flat-square)](https://shamsul.serve.scilifelab.se/)

<a href="https://shamsul.serve.scilifelab.se/">
  <img src="https://raw.githubusercontent.com/anondo1969/SHAMSUL/main/SHAMSUL_demo_app_screengrab.png" alt="SHAMSUL demo app" width="720">
</a>

**Main themes:** explainable AI · Grad-CAM · LRP · LIME · SHAP · medical imaging · model interpretation · clinical decision support

---

## Other presentations from the PhD years

Some related publications are not part of the six-paper thesis core, but their presentation material is still useful:

- **Terminology expansion with prototype embeddings (2021):** [slides](https://mahbub.blogs.dsv.su.se/files/2021/02/HEALTHINF_2021_presentation_slides_Mahbub_Ul_Alam.pdf)
- **Intelligent context-based healthcare metadata aggregator (2020):** [presentation video](https://mahbub.blogs.dsv.su.se/files/2022/05/presentation.mp4)
- **Deep learning from sparse medical data for early sepsis prediction (2020):** [slides](https://mahbub.blogs.dsv.su.se/files/2020/04/HEALTHINF_2020_presentation_slides_Mahbub_Ul_Alam.pdf) · [presentation video](https://mahbub.blogs.dsv.su.se/files/2022/05/early_detection_of_sepsis_Mahbub_Ul_Alam.mp4)

The full set is also available on the [presentation resources page](https://mahbub.blogs.dsv.su.se/publication-presentation-slides/).

---

## Earlier research — Master's thesis

### From Speech to Image

**From Speech to Image: A Novel Approach to Understand the Hidden Layer Mechanisms of Deep Neural Networks in Automatic Speech Recognition**  
Master's thesis, University of Stuttgart, 2017.

This project visualizes internal neural-network representations in automatic speech recognition. It was my earlier work on model interpretation, before the medical-imaging projects in the PhD.

[![Code](https://img.shields.io/badge/GitHub-Code-181717?style=flat-square&logo=github)](https://github.com/anondo1969/deep-speech-vis)
[![Thesis](https://img.shields.io/badge/DOI-Thesis-B31B1B?style=flat-square)](http://dx.doi.org/10.13140/RG.2.2.18693.01765)
[![Slides](https://img.shields.io/badge/Slides-Google%20Drive-0078D4?style=flat-square)](https://drive.google.com/file/d/1vN8bIXMk_q4KN0DC6-5jkPPzjueLDuqu/view)

**Main themes:** speech recognition · interpretability · LRP · TensorFlow · Kaldi · neural networks

---

## About this archive

This repository is an index, not a replacement for the original research repositories. Keeping the original repositories public means code links used in the thesis and publications can continue to work. The archive simply gives the research record one place on GitHub, leaving the main profile free to highlight current engineering work.
