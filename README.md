# Transformers Notes

A concise companion README for the `Transformers.ipynb` notebook in this folder.

## Overview
- Notebook: `Transformers.ipynb`
- Purpose: Notes, explanations and runnable examples covering Transformer architectures (attention, encoder/decoder stacks, BERT, GPT-style models, positional encodings, and training tips).

## Prerequisites
- Python 3.8+ recommended
- JupyterLab or Jupyter Notebook
- Optional libraries for code cells: `numpy`, `torch`, `tensorflow`, `transformers` (Hugging Face)

## Quick start
1. Create and activate a virtual environment (optional but recommended):

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Install Jupyter and common libraries (adjust as needed):

```bash
pip install --upgrade pip
pip install jupyterlab numpy torch transformers
```

3. Open the notebook:

```bash
jupyter lab
# or
jupyter notebook
```

Then open `Transformers.ipynb` in the browser.

## Notes
- Some example cells may assume GPU availability (PyTorch/CUDA). If you don't have a GPU, run on CPU or adjust batch sizes.
- If you want a requirements file added, I can generate `requirements.txt` listing the used packages.

