![LOGO](https://github.com/omarmohamed15/Convmixer_EEWS/blob/main/Assest/ConvMixer_EEWS.png)

# ConvMixer Network for Joint Earthquake Detection, Location, and Magnitude Estimation in Earthquake Early Warning Systems

---

## Overview

Earthquake Early Warning Systems (EEWS) require rapid and reliable estimation of earthquake occurrence and source parameters. This repository provides pretrained models and evaluation notebooks for **ConvMixer-EEWS**, a deep learning framework that jointly performs:

- Earthquake Detection
- Earthquake Location Estimation
- Earthquake Magnitude Estimation

using only single-station three-component seismic waveforms.

Unlike conventional multi-stage workflows, the proposed framework learns all tasks simultaneously within a unified ConvMixer architecture, enabling efficient and accurate real-time earthquake monitoring.

---

## Highlights

- Joint earthquake detection, location, and magnitude estimation.
- ConvMixer-based architecture for seismic waveform analysis.
- Single-station Earthquake Early Warning System (EEWS).
- Pretrained models provided.
- Tested on multiple large-scale seismic datasets.
- Publication-quality evaluation and visualization notebooks.

---

## Repository Structure

```text
ConvMixer-EEWS/
│
├── data/
│
├── pretrained_models/
│
├── Instance-EEWS ConvMixer_test.ipynb
├── STEAD-EEWS ConvMixer_test.ipynb
├── Texas-EEWS ConvMixer_test.ipynb
│
└── README.md
```

### Directory Description

| File / Folder | Description |
|---------------|-------------|
| `data/` | Example seismic data used for evaluation |
| `pretrained_models/` | Pretrained ConvMixer models |
| `STEAD-EEWS ConvMixer_test.ipynb` | Evaluation notebook for the STEAD dataset |
| `Instance-EEWS ConvMixer_test.ipynb` | Evaluation notebook for the INSTANCE dataset |
| `Texas-EEWS ConvMixer_test.ipynb` | Evaluation notebook for the TXED dataset |

---

## Datasets

The framework has been evaluated on three benchmark seismic datasets:

| Dataset | Description |
|----------|------------|
| STEAD | Stanford Earthquake Dataset |
| INSTANCE | Italian Seismic Dataset |
| TXED | Texas Earthquake Dataset |

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/ConvMixer-EEWS.git
cd ConvMixer-EEWS
```

Install the required dependencies:

```bash
pip install tensorflow-gpu numpy matplotlib obspy
```

---

## Running the Evaluation Notebooks

### STEAD

```bash
jupyter notebook "STEAD-EEWS ConvMixer_test.ipynb"
```

### INSTANCE

```bash
jupyter notebook "Instance-EEWS ConvMixer_test.ipynb"
```

### TXED

```bash
jupyter notebook "Texas-EEWS ConvMixer_test.ipynb"
```

Each notebook:

- Loads the pretrained ConvMixer model.
- Performs inference on unseen seismic waveforms.
- Computes earthquake detection metrics.
- Evaluates location estimation performance.
- Evaluates magnitude estimation performance.
- Generates publication-quality figures.

---

## Evaluation Metrics

### Earthquake Detection

- Accuracy
- Precision
- Recall
- F1-score

### Earthquake Location

- Latitude Error
- Longitude Error
- Depth Error
- Epicentral Distance Error

### Magnitude Estimation

- Mean Absolute Error (MAE)
- Standard Deviation (STD)

---

## Authors

- Hagar S. Elsayed
- Omar M. Saad
- Chao Li
- Yangkang Chen

---

## Contact

**Omar M. Saad**  

📧 engomar91@gmail.com

---
