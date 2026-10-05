# DL4STG Assignment 1 (AI651 / Fall 2026)

Muhammad Tayyab Tahir Qureshi, roll number 25280024.

The writeup for both tasks is [`report.pdf`](report.pdf). The source is [`report.tex`](report.tex).

## Layout

- `report.pdf` and `report.tex` sit at the root. This is the report to upload.
- `Task1/` is the forecasting notebook, the harness, and the full-run tables and figures.
- `Task2/` is the 168-step forecast. The submitted line is `Task2/outputs/submission_168.txt`. `P` and `E` are in `Task2/outputs/manifest.json`.

## Task 1

```bash
cd Task1
python -m venv .venv
python -m pip install -r requirements.txt
```

Open `Assignment1.ipynb` and run all cells. The setup cell uses `PA1_PRESET=full`.

## Task 2

The course CSVs are not in this repository. Place these three files where the notebook can see them:

- `student_train.csv`
- `student_test.csv`
- `optional_external_data.csv`

`Task2.ipynb` looks in `../Question 2 - Leaderboard/Data`, then in `/content/data`.

```bash
cd Task2
python -m pip install -r requirements.txt
```

Open `Task2.ipynb` and run all cells.
