# CalmQuest — Duolingo Stress Monitor & Dataset

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Colab](https://img.shields.io/badge/Open%20In-Colab-F9AB00.svg?logo=googlecolab)](https://colab.research.google.com/github/umarnasir123/stress-dataset-/blob/main/CalmQuest_Duolingo_Stress_Monitor_Colab.ipynb)
[![Dataset](https://img.shields.io/badge/Dataset-70%20Participants-2ea44f.svg)](#dataset-overview)
[![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)](#license)

> **CalmQuest** is a stress monitoring dataset and Google Colab analysis workflow studying user stress signals across **70 participants** in a Duolingo / language-learning context (`stress_monitoring_70_participants.csv`).

---

## Table of Contents

- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Dataset Overview](#dataset-overview)
  - [Schema & Feature Dictionary](#schema--feature-dictionary)
  - [Data Quality & Preprocessing](#data-quality--preprocessing)
- [Quickstart & Usage](#quickstart--usage)
  - [Run in Google Colab](#run-in-google-colab)
  - [Local Setup](#local-setup)
- [Methodology & Modeling Pipeline](#methodology--modeling-pipeline)
- [Experimental Results](#experimental-results)
- [Roadmap & Versioning](#roadmap--versioning)
- [Ethics, Privacy & Limitations](#ethics-privacy--limitations)
- [Citation & Contact](#citation--contact)

---

## Project Overview

Language learning under time pressure, streaks, and cognitive load can trigger measurable shifts in user stress and engagement. This repository provides:

1. **Participant Dataset (`stress_monitoring_70_participants.csv`)**: Stress monitoring records covering **70 participants**.
2. **Analysis & Modeling Notebook (`CalmQuest_Duolingo_Stress_Monitor_Colab.ipynb`)**: End-to-end exploratory data analysis (EDA), feature engineering, stress classification/regression experiments, and visualization designed for Google Colab.

---

## Repository Structure

```text
stress-dataset-/
├── CalmQuest_Duolingo_Stress_Monitor_Colab.ipynb   # Main Colab notebook (EDA, preprocessing, modeling, plots)
├── stress_monitoring_70_participants.csv           # Dataset covering 70 participants
└── README.md                                       # Project documentation
