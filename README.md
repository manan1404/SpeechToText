# Speech Project: Accent Classification

## Overview
This project focuses on accent classification using audio data. It uses deep learning libraries to process and analyze audio files, aiming to accurately predict accents based on the provided dataset (https://www.kaggle.com/datasets/mozillaorg/common-voice).

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Dependencies](#dependencies)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/manan1404/speechproj-stt-accent.git
   cd speechproj-stt-accent
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your dataset in the specified format.
2. Run the main script:
   ```bash
   python main.py
   ```
   Replace `main.py` with the actual script name if different or download the ipynb file attached and execute every cell in Kaggle.

## Data
The dataset used for this project can be found in the `/kaggle/input/common-voice/` directory. It includes audio samples along with their corresponding accents and genders.

## Dependencies
The project requires the following Python packages:
- pandas
- numpy
- torch
- transformers
- torchaudio
- evaluate
- datasets
- mlflow
- SpeechRecognition
- imblearn
- tqdm
- matplotlib
- scikit-learn

Refer to `requirements.txt` for exact versions of the libraries.
