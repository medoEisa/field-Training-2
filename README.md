# Arabic Hate Speech
This research investigates various models for detecting hate speech in Arabic text. The study evaluates classical machine learning algorithms, advanced deep learning techniques, and Transformer models. The goal is to develop a robust system for hate speech detection that addresses the challenges posed by the Arabic language’s complex morphology, extensive vocabulary, and diverse dialects.

Project overview
- **Purpose:** This repository contains experiments, data, and notebooks for Arabic hate-speech detection and Arabic language model experiments under the SRTA project.
- **Scope:** classical ML baselines, neural architectures, and transformer-based models (MARBERT, AraT5/AraGPT variants). The materials include datasets, training notebooks, and evaluation code used for experiments.

Repository structure
- `other/` : Additional or archival notebooks and experiments.
  - `Hate_Speech_v1 (1) (1).ipynb` — archived/alternate version of early hate-speech experiments. Inspect the notebook for details and notes.
  - `MARBERT_V0.ipynb` — experimental notebook using the MARBERT model (version 0) for Arabic classification.
  - `Gui.ipynb` — 'User Interface for the system with options to select the suitable model '
  - `DEMO.mp4` — Screen Record for this system

- `project/` : Main project files and notebooks used for the SARTA experiments.
  - `[Part_1]Hate-Speech-Detection_Classical-ML.ipynb` — classical machine learning baselines (feature extraction, vectorizers, SVM/Logistic Regression/RandomForest, metrics and analysis).
  - `[Part_2]Hate-Speech-Detection_Neural-Learning-Models.ipynb` — neural-network based approaches (LSTM/CNN/other non-transformer models) and training/evaluation loops.
  - `ARAGPT-2_V0.ipynb` — experiments fine-tuning or using an AraGPT-2-style model for generation or classification tasks.
  - `AraT5_v0.ipynb` — experiments with AraT5 (T5-based) models for sequence-to-sequence tasks, augmentation, or classification framing.
  - `MARBERT_V0.ipynb` — MARBERT experiments within the main project (may overlap with `other/`).
  - `Hate_Speech_v0.ipynb`, `Hate_Speech_v1.ipynb` — iterative hate-speech notebooks; check individual versions for methodology differences.
  - `dev_data.csv` — development/validation dataset (used for hyperparameter tuning and validation).
  - `test_dataset.csv` — test set used for final evaluation.
  - `train_dataset.csv` — training dataset used to fit models.
