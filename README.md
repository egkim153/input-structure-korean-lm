# input-structure-korean-lm
Korean grammar learning with structured input

# Investigating the Effects of Input Structure on Korean Grammar Learning

This repository contains the data, code, and figures used for the BUCLD 2024 abstract:  
**“Investigating the Effects of Input Structure on Korean Grammar Learning in Language Models.”**

## 📂 Repository Structure
- `data/` – Training data (Original, Curriculum, Variation Sets, Translated)
- `scripts/` – Training and evaluation code
- `figures/` – Visualizations: perplexity chart, input table
- `results/` – Evaluation output files
- `environment.yml` – Reproducible conda environment file

## 🛠 How to Run

```bash
conda env create -f environment.yml
conda activate korean-lm
python scripts/train.py --condition original
