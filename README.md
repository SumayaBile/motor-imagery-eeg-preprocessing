# Motor Imagery EEG Preprocessing

This project is dedicated to the preprocessing of EEG (electroencephalogram) data for motor imagery (MI) tasks. The aim is to apply various signal processing techniques to raw EEG data to extract useful features for machine learning applications, particularly in Brain-Computer Interface (BCI) systems. This repository showcases the key steps of EEG preprocessing, including filtering, artifact removal, and feature extraction, in order to make the data ready for further analysis or predictive modeling.

## Project Overview

Motor imagery refers to the process of mentally simulating a movement without physically executing it. EEG signals are commonly used to capture brain activity associated with motor imagery tasks. This project focuses on preprocessing raw EEG signals collected during motor imagery experiments. The key steps include:

1. **Data Cleaning and Filtering**: The raw EEG data can be noisy and contains unwanted signals (e.g., from muscle movements or eye blinks). We apply filtering techniques to remove noise and retain the relevant frequency bands.

2. **Artifact Removal**: Artifacts in EEG signals (such as eye movements or muscle contractions) can distort the data. We apply methods to identify and remove these artifacts to improve the signal quality.

3. **Feature Extraction**: The clean EEG data is then processed to extract meaningful features, such as power spectral density, that can be used for subsequent machine learning tasks.

4. **Data Visualization**: The processed EEG signals and extracted features are visualized for better understanding and analysis.

## Project Goals

- To provide a comprehensive preprocessing pipeline for motor imagery EEG data.
- To demonstrate the practical use of signal processing techniques such as filtering, artifact removal, and feature extraction.
- To create a reusable, well-documented codebase that can be applied to other EEG-related tasks in brain-computer interfaces (BCIs) or neuroscience research.

## Structure of the Repository

- `Untitled27.ipynb`: This Jupyter notebook demonstrates the entire preprocessing pipeline. It walks through loading raw EEG data, applying filtering techniques, removing artifacts, and extracting features. The notebook also includes visualizations to display the processed data.

- `pa_3_labeled.csv`: A sample dataset of labeled EEG data used for this project. The dataset is processed through various steps in the notebook.

- `.ipynb_checkpoints`: Contains Jupyter notebook checkpoints.

- `.gitignore`: Specifies files and directories that should be ignored by Git, such as `.ipynb_checkpoints/`.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/SumayaBile/motor-imagery-eeg-preprocessing.git
