# Speech Emotion Recognition Experiments

This repository contains the code for the ASR report, implemented in the Jupyter Notebook `ASR_Code.ipynb`.

## Setup

1.  **Clone Repo:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Download Data:**
    This project requires the TESS, RAVDESS, SAVEE, CREMA-D, EMO-DB, ASED, and DAIC-WOZ datasets, as well as the `best_model_mfcc_attention.pth` pre-trained model file.

4.  **Update Paths:**
    Open `ASR_Code.ipynb` and **edit all the paths** in the `CFG` class (Cell #3) to point to your local dataset locations.

## How to Run

1.  Open the `ASR_Code.ipynb` notebook.
2.  In the first code cell, set the `RUN_...` flags to `True` for the experiments you wish to run.
    ```python
    RUN_COMPREHENSIVE_COMPARISON = True
    RUN_CROSS_LINGUAL_EVALUATION = True
    RUN_DEPRESSION_DETECTION = True
    ```
3.  Run all cells in the notebook to execute the selected experiments.
