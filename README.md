# COVID-19 Chest X-ray Segmentations Dataset

![COVID-19](https://user-images.githubusercontent.com/66736646/88059973-64c6e000-cb87-11ea-90fe-ee6c346879ff.png)

## Intro

<!--
<img src="https://user-images.githubusercontent.com/33668152/86773453-7ed8cc80-c077-11ea-975a-b917800389a4.png" alt="X-ray" align="right" width="300" />
-->

Segmentations of COVID-19 Chest X-ray Dataset.

Go [here](#download-the-dataset) if you don't have time.

<p align="center"><img src="https://user-images.githubusercontent.com/66736646/89189135-60f08000-d5c1-11ea-87cc-bb10b8bb635a.gif" /></p>

---

## Table of Contents

- [Motivation](#motivation)
- [About the Dataset](#about-the-dataset)
- [Download the Dataset](#download-the-dataset)
- [Links and References](#links-and-references)
- [Who are we](#who-are-we)
- [Contact us](#contact-us)
- [License](#license)

---

## Motivation

In this pandemic situation, our aim is to help researchers to find out a solution. In order to do that we are aiming to provide them with proper datasets that makes the process easier.

A [repository](https://github.com/ieee8023/covid-chestxray-dataset) to build a public open dataset of chest X-ray and CT images of patients which are positive or suspected of COVID-19 or other viral and bacterial pneumonias (MERS, SARS, and ARDS.) was created by [Joseph Paul Cohen](https://github.com/ieee8023). Data have been collected from public sources as well as through indirect collection from hospitals and physicians.

We are providing segmentations of those publicly available datasets.

---

## About the Dataset

This dataset is a total collection of 100 images with Segmentations of Chest X-ray Dataset of Novel Coronavirus (COVID-19) Cases. The annotation file is in COCO format.

Each annotation contains segmentations of Anatomical classes (Left lung, Right lung, Cardiomediastinum, Airways), Pathology classes (Ground glass opacities, Consolidation, Pleural effusion, Pneumothorax), Objects (Endotracheal tube, Central veinous line, Monitoring probes, Nasogastric tube, Chest tube, Tubings). Each image was manually annotated by qualified radiologists.

**Warning:** Do not claim diagnostic performance of a model without a clinical study!

| No        | Category           | Images  | Masks  |
| ------------- |:-------------:| -----:| -----:|
| 1          |    Right Lung        | 616 | 616 |

---

## Download the Dataset

### Download the dataset as zip format

![Download zip](https://user-images.githubusercontent.com/33668152/88057901-8e323c80-cb84-11ea-85de-9835d979f6e7.png)

### Download using git clone

Open terminal and run the following command:

```
git clone https://github.com/GeneralBlockchain/covid-19-chest-xray-segmentations-dataset.git
```

## Links and References

- Dataset homepage: https://github.com/GeneralBlockchain/covid-19-chest-xray-segmentations-dataset

- Repository: https://github.com/GeneralBlockchain/covid-19-chest-xray-segmentations-dataset.git

- Issue tracker: https://github.com/GeneralBlockchain/covid-19-chest-xray-segmentations-dataset/issues

- Image source: https://github.com/ieee8023/covid-chestxray-dataset
<!--
- Joseph Paul Cohen, Paul Morrison, Lan Dao, "COVID-19 Image Data Collection" - [paper](https://arxiv.org/abs/2003.11597)
-->
<!--
- Joseph Paul Cohen, Paul Morrison, Lan Dao, Karsten Roth, Tim Q Duong, Marzyeh Ghassemi, "COVID-19 Image Data Collection: Prospective Predictions Are the Future" - [paper](https://arxiv.org/abs/2006.11988)
-->
- In case of any help you may need from us, please [contact us](#contact-us) directly without any hesitation! We will be glad to help you.

---

## Who are we

We are **[General Blockchain Inc](https://www.generalblockchain.com/)**, a company developing technology to support the AI industry using blockchain technology.

Our vision is to build a programmable, human based, artificial intelligence.

The first application of this human computer is to provide image annotation services to the machine learning and artificial intelligence community.

Please access our Image Annotation AI services [here](https://www.imageannotation.ai/), today.

---

## Contact Us

* Email: contact@generalblockchain.com

---

## License

Each image has license specified in the [metadata.csv](https://github.com/GeneralBlockchain/covid-19-chest-xray-segmentations-dataset/blob/master/metadata.csv) file. Including Apache 2.0, CC BY-NC-SA 4.0, CC BY 4.0.

The repository is licensed under [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

### Special thanks to the following radiologists who worked to the best of their ability to make our research possible:

Dr. Ayoub El Hajjami

Dr. Mohamed Soliman

---



