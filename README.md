# COMP9444 Group Project

Environmental sound classification on the ESC-50 dataset using convolutional and recurrent neural networks.

## Project plan

1. Prepare ESC-50 audio and official cross-validation folds.
2. Convert audio clips to log-Mel spectrograms.
3. Train a CNN baseline.
4. Train and evaluate a CRNN using a CNN encoder and GRU/LSTM.
5. Compare models across the official folds and report mean accuracy and standard deviation.

## Repository structure

- `notebooks/`: exploration and experiment notebooks
- `src/`: reusable data, model, training, and evaluation code
- `data/`: local datasets (not committed)
- `models/`: local checkpoints (not committed)
- `results/`: metrics, plots, and confusion matrices
- `report/`: written report material
- `slides/`: presentation material

## Setup

```bash
python -m venv .venv
python -m pip install -r requirements.txt
```

Download ESC-50 from <https://github.com/karolpiczak/ESC-50> and place it under `data/ESC-50/`.

