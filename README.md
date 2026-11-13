<p align="center"><img src="docs/assets/banner.svg" alt="HeartDiseaseNN — A neural-network study of structured heart-health data." width="100%"></p>

<p align="center"><img src="docs/assets/badges/python.svg" alt="python" height="28"> <img src="docs/assets/badges/tensorflow.svg" alt="tensorflow" height="28"> <img src="docs/assets/badges/keras.svg" alt="keras" height="28"> <img src="docs/assets/badges/scikit-learn.svg" alt="scikit-learn" height="28"></p>

<p align="center"><strong>A Colab-oriented TensorFlow workflow for preprocessing tabular heart-disease data, training a neural network, and inspecting predictions.</strong></p>

## Overview

A Colab-oriented TensorFlow workflow for preprocessing tabular heart-disease data, training a neural network, and inspecting predictions.

### Why it matters

HeartDiseaseNN packages the major steps of a supervised deep-learning experiment into one readable notebook-derived script, from upload to interpretation.

## Key features

- Categorical encoding and numeric standardization
- Dense neural network with dropout
- Validation plots and confusion-matrix review
- Permutation-based feature importance

## Architecture

```mermaid
flowchart LR
  A[Uploaded CSV] --> B[Encode + standardize]
  B --> C[Train / validation split]
  C --> D[Dense neural network]
  D --> E[Prediction review]
  E --> F[Feature importance]
```

## Technology stack

**python** · **tensorflow** · **keras** · **scikit learn**

## Getting started

Open `heartdisease_nn_.py` in Google Colab or convert its notebook-style commands to a local notebook. Upload a compatible CSV with a `HeartDisease` target. This is an educational workflow, not a clinical tool.
