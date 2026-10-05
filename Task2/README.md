# Task 2

Open `Task2.ipynb` and run it from top to bottom. That notebook is the whole solution: data, a small Autoformer, the covariate ablation, and the 168-step submission.

```bash
pip install -r requirements.txt
```

The CSVs are read from `../Question 2 - Leaderboard/Data` (or `/content/data` on Colab):

- `student_train.csv`
- `student_test.csv`
- `optional_external_data.csv`

The notebook writes `outputs/submission_168.txt` and `outputs/manifest.json`. Paste the forecast line on the leaderboard, and enter `P` and `E` from the manifest.
