# Tutorial 4: ADMET Property Prediction and Toxicity Profiling of CDK2 Inhibitors

## A Comprehensive Cheminformatics Tutorial Using ADMET-AI 2.0 and RDKit

**Authors:** Jane O. Anebi, Festus O. Ogungbemiro & Felix O. Okunlola
**Institution:** CBIOS – Research Center for Biosciences & Health Technologies, Universidade Lusofona, Lisboa, Portugal; Department of Biochemistry and Biotechnology, Nile University of Nigeria, Abuja, Nigeria

---

# Overview

This repository contains a comprehensive educational Jupyter notebook for large-scale computational ADMET profiling of cyclin-dependent kinase 2 (CDK2) inhibitors using ADMET-AI 2.0, RDKit, and Python-based cheminformatics workflows.

The tutorial demonstrates a complete and reproducible workflow for predicting Absorption, Distribution, Metabolism, Excretion, and Toxicity (ADMET) properties of small molecules using graph neural network-based prediction models integrated with cheminformatics analysis pipelines.

The notebook is designed for:

* Computational drug discovery researchers
* Cheminformatics and bioinformatics students
* Medicinal chemists
* Pharmacology and toxicology researchers
* Graduate-level teaching and workshops
* Reproducible computational research training

The workflow analyses 200 curated CDK2 inhibitors from ChEMBL release 35 and generates comprehensive ADMET profiles across 104 predictive properties.

---

# Key Features

* Fully annotated educational notebook
* Reproducible ADMET prediction workflow
* Integration of ADMET-AI 2.0 and RDKit
* Multi-endpoint ADMET prediction
* Drug-likeness and structural alert analysis
* CYP450 metabolism profiling
* Toxicity and Tox21 pathway prediction
* DrugBank approved-drug percentile benchmarking
* Composite ADMET scoring framework
* Traffic-light visualisation system
* Automated CSV export of integrated ADMET profiles
* FAIR and open-science oriented workflow

---

# Scientific Scope

| Domain                       | Analysis Included                                |
| ---------------------------- | ------------------------------------------------ |
| Physicochemical Profiling    | Molecular descriptors, lipophilicity, solubility |
| Drug-Likeness                | Lipinski Ro5, PAINS, Brenk, NIH filters          |
| Absorption                   | HIA, Caco-2, PAMPA, Pgp, bioavailability         |
| Distribution                 | BBB permeability, VDss, PPBR                     |
| Metabolism                   | CYP450 inhibition and substrate profiling        |
| Excretion                    | Clearance and half-life predictions              |
| Toxicity                     | hERG, AMES, DILI, ClinTox, LD50, carcinogenicity |
| Tox21 Profiling              | Nuclear receptor and stress response pathways    |
| Benchmarking                 | DrugBank percentile ranking analysis             |
| Multi-Parameter Optimisation | Composite ADMET scoring and ranking              |

---

# Workflow Structure

| Cell    | Section                                     |
| ------- | ------------------------------------------- |
| Cell 0  | Environment Setup and Version Validation    |
| Cell 0B | Python and Cheminformatics Fundamentals     |
| Cell 1  | CDK2 Dataset Construction                   |
| Cell 2  | ADMET-AI Prediction Pipeline                |
| Cell 3  | Physicochemical Property Profiling          |
| Cell 4  | Drug-Likeness and Structural Alert Analysis |
| Cell 5  | Absorption Property Profiling               |
| Cell 6  | Distribution Property Profiling             |
| Cell 7  | CYP450 Metabolism Analysis                  |
| Cell 8  | Excretion Profiling                         |
| Cell 9  | Toxicity Profiling                          |
| Cell 10 | Tox21 Pathway Profiling                     |
| Cell 11 | DrugBank Percentile Benchmarking            |
| Cell 12 | ADMET Traffic-Light Dashboard               |
| Cell 13 | Composite ADMET Scoring                     |
| Cell 14 | 2D Structure Grid Visualisation             |
| Cell 15 | Integrated Report Export                    |

---

# Software Requirements

## Core Dependencies

* Python 3.10+
* RDKit
* ADMET-AI 2.0
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* torch
* pytorch-lightning

---

# Installation

## 1. Clone the Repository

```bash
git clone https://github.com/your-repository/cdk2-admet-tutorial.git
cd cdk2-admet-tutorial
```

## 2. Create a Conda Environment

```bash
conda create -n admet_tutorial python=3.10
conda activate admet_tutorial
```

## 3. Install RDKit

```bash
conda install -c conda-forge rdkit
```

## 4. Install Python Packages

```bash
pip install pandas numpy matplotlib seaborn scikit-learn torch pytorch-lightning jupyter
```

## 5. Install ADMET-AI

Follow installation instructions from the official ADMET-AI repository/documentation.

---

# Running the Notebook

```bash
jupyter notebook
```

Open:

```text
cdk2_admet_tutorial4.ipynb
```

Run cells sequentially from Cell 0 to Cell 15.

---

# Educational Objectives

After completing this tutorial, users should be able to:

1. Understand ADMET concepts in computational drug discovery
2. Perform large-scale ADMET prediction using ADMET-AI 2.0
3. Apply RDKit for molecular processing and descriptor analysis
4. Interpret pharmacokinetic and toxicity endpoints
5. Evaluate drug-likeness and structural alerts
6. Implement multi-parameter optimisation strategies
7. Generate reproducible cheminformatics workflows

---

# Reproducibility and FAIR Principles

The notebook follows reproducible research and FAIR data principles:

* Findable workflow structure
* Accessible open-source tools
* Interoperable Python ecosystem
* Reusable educational framework
* Transparent computational methodology
* Version-controlled analysis pipeline

---

# Citation

```text
Anebi JO, Ogungbemiro FO, Okunlola FO.
Tutorial 4: ADMET Property Prediction and Toxicity Profiling of CDK2 Inhibitors.
A Comprehensive Cheminformatics Tutorial Using ADMET-AI 2.0 and RDKit.
```

---

# License

Specify the repository license here (e.g., MIT, BSD-3-Clause, CC BY 4.0).

---

# Contact

* Festus O. Ogungbemiro
* CBIOS – Universidade Lusofona
* Lisboa, Portugal
