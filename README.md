# Automatic-Assesment-of-Mother-Tongue-Reading-Ability
This repository contains an acoustic model designed to help young children pronounce words and phonemes accurately. The model is pre-trained and leverages the Connectionist Temporal Classification (CTC) algorithm for effective speech recognition and alignment.

## Model Overview

- **Purpose**: The model aids young learners in pronouncing words and phonemes correctly.
- **Algorithm**: The core of the model is built on the CTC (Connectionist Temporal Classification) algorithm, which is well-suited for sequence-to-sequence problems like speech recognition.
- **Training**: During the training phase, the model employs the Forward-Backward Algorithm to optimize the alignment of input speech sequences with the target phonetic sequences.

## Theory and Implementation

A brief theoretical overview of the CTC algorithm and the Forward-Backward Algorithm used in the training phase is provided here.
The link for the same is:

[Powerpoint Presentation](https://1drv.ms/p/s!Apz3XPqGFRE0iCpZgSh1_1BQ--s3?e=mYQXZx)


## Pre-trained Model

The pre-trained model can be downloaded from the following link:

[Download Pre-trained Model](https://drive.google.com/file/d/11vajzj4GucJBgmp17Mz8com2I4PFUMtx/view?usp=sharing)

## Getting Started

To use this model, follow the instructions below:

We recommend using [Google Colab](https://colab.research.google.com) for running the model as it provides free GPU access and an easy-to-use environment.

1. **Open Google Colab** and create a new notebook.

2. **Download ipynb file** and copy the code in your notebook.

3. **Record your voice** in `.wav` format and upload it to your notebook, naming the audio file `audio.wav`.

4. **Download the pre-trained model** to your Google Drive. This step is necessary because the model will be loaded from your Drive. If you prefer to load it from another source, please update the loading path in the third cell of the notebook accordingly.

5. **Run the cells** in the notebook sequentially to get your letter and word level pronunciation scores.

By following these steps, you can enhance your pronunciation accuracy effectively.

---

Feel free to explore the code, experiment with the model, and help young learners improve their pronunciation skills!
