# DL4STG Assignment 1 (AI651 / Fall 2026)

Public repository for Assignment 1.

## Contents

- `Task1/` : `Assignment1.ipynb`, `harness/`, `requirements.txt`, and `results/` from a `PA1_PRESET=full` run on CUDA
- `report/` : LaTeX source and PDF for the Task 1 responses

## How to run Task 1

```bash
cd Task1
python -m venv .venv
# Windows: .venv\Scripts\Activate.ps1
# Linux/macOS: source .venv/bin/activate
python -m pip install -r requirements.txt
```

Set `PA1_PRESET=full` for report evidence (the submitted notebook setup cell already does this). Use `smoke` only while debugging.

Open `Assignment1.ipynb` and run all cells.

## Note

Task 2 (leaderboard) is not included in this repository package.
