<div align="center">

# Med-VQA Survey

### A descriptive look at nine Medical Visual Question Answering benchmarks

**Exploratory analysis and visualizations to understand how questions about medical images are asked and answered.**

[![Notebooks for Google Colab](https://img.shields.io/badge/Open_notebooks-Google_Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/AlbertP97/Med-VQA-Survey/)
![Notebooks](https://img.shields.io/badge/notebooks-9-3978A8)
![Focus](https://img.shields.io/badge/focus-descriptive_analysis-2A9D8F)

<img src="assets/med-vqa-overview.svg" alt="Illustration of question answering and analysis of medical images" width="100%">

</div>

## About

This repository accompanies a survey of **Medical Visual Question Answering (Med-VQA)**. It contains nine Jupyter notebooks, one for each benchmark, reproducing descriptive statistical analyses and visualizations of their data. The goal is to make it easier to explore the characteristics of each dataset—and how they differ—not to train or compare models.

Depending on the fields available in each dataset, the notebooks explore aspects such as the number of images, questions, and answers; the frequency of question and answer types; common questions and answers; text length; and distributions or relationships between variables such as modality, anatomy, organ, or difficulty. The scope and variables **are not identical across all notebooks**.

## Notebooks

| Benchmark | Notebook | Highlights |
| --- | --- | --- |
| DME-VQA | [DME_VQA.ipynb](DME_VQA.ipynb) | Question types and frequent questions and answers; breakdowns by type and center. |
| Kvasir-VQA | [Kvasir_VQA.ipynb](Kvasir_VQA.ipynb) | Complexity, frequent questions and answers, and text length. |
| MedFrameVQA | [MedFrameVQA.ipynb](MedFrameVQA.ipynb) | Distributions by modality, organ, and system, as well as question and answer lengths. |
| PMC-VQA | [PMC_VQA.ipynb](PMC_VQA.ipynb) | Radiological content, answer options, and text and caption statistics. |
| PathVQA | [PathVQA.ipynb](PathVQA.ipynb) | Question and answer types, frequencies, and length distributions. |
| SLAKE | [SLAKE.ipynb](SLAKE.ipynb) | Answer types, frequent questions, and cross-variable analyses. |
| VQA-MED 2019 | [VQA_MED_2019.ipynb](VQA_MED_2019.ipynb) | Descriptive analysis of questions, answers, and images. |
| VQA-RAD | [VQA_RAD.ipynb](VQA_RAD.ipynb) | Questions and answers by type, organ breakdowns, and a visual summary. |
| ViDr-CXR-VQA | [ViDr_CXR_VQA.ipynb](ViDr_CXR_VQA.ipynb) | Image-level and question-answer pair analyses, including difficulty and justifications. |

## Getting started

1. Open the notebook for the benchmark you want to explore (the table links to GitHub and Google Colab).
2. Check the first cells: each notebook documents its dependencies and its own data-loading approach.
3. Provide the data files expected by that notebook—using Colab's upload feature or the specified path, for example—and run the cells in order.
4. Explore the resulting tables, statistics, and charts; adjust paths or loading settings as needed for your environment.

> **Data:** The notebooks are versioned here, but the datasets are not. Data access, format, and filenames may differ between benchmarks; consult the relevant notebook and obtain the data from its authorized source.

## Repository structure

```text
.
├── DME_VQA.ipynb
├── Kvasir_VQA.ipynb
├── MedFrameVQA.ipynb
├── PMC_VQA.ipynb
├── PathVQA.ipynb
├── SLAKE.ipynb
├── VQA_MED_2019.ipynb
├── VQA_RAD.ipynb
├── ViDr_CXR_VQA.ipynb
├── assets/
│   └── med-vqa-overview.svg
└── README.md
```

## Scope and responsible use

These notebooks are intended for **research data exploration and analysis**; they are not diagnostic or clinical decision-support tools. Before downloading or using a dataset, review its access terms, license, and ethical requirements. Results may depend on the version, preprocessing, and files provided to each notebook.

## Citation

This code reproduces analyses and visualizations related to a Med-VQA survey.
