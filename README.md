# 25ws-42.17

Repository template for the 42.17 "Societal challenges datathon" course at RWTH

- Fork this repo
- Work in your own fork and update changes there
- Use the `main.ipynb` for your main results, you can create other notebooks for accessory work if you so desire

## Create the virtual environment

Install the [uv python package manager](https://docs.astral.sh/uv/#installation).

Run the following in your console

```bash
uv sync
```


## Starting

**jupyter lab**

- `uv run jupyter lab`

**vscode**

- Open the notebook and select the right kernel

# Course Submission: submission_notebook.ipynb

## Overview
This repository contains the main notebook `submission_notebook.ipynb`, which includes all analyses, models, and results for the project.

## Running the Notebook
1. Open `submission_notebook.ipynb` in Jupyter Notebook.
2. Run all cells sequentially.
3. All outputs (plots, summaries, and results) will be saved in the `outputs` folder.

## Outputs Folder Structure
```
```
outputs/
├── EDA/          # Exploratory Data Analysis plots and summaries
├── ensemble/     # Ensemble model results
├── model_1/      # Model 1 outputs
├── model_2/      # Model 2 outputs
└── summaries/    # Summaries of columns

## Note
- All required dependencies are included in the notebook itself.
- The notebook is self-contained; all steps from data loading to model evaluation are included.
