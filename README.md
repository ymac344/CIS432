# CIS432 – Machine Learning for Business Analytics

Homework assignments for CIS432 (Simon Business School). Instructor: Yaron Shaposhnik.

## Homework: the HELOC dataset

| Part | Topic | Open in Colab |
|------|-------|---------------|
| 1 | Data wrangling and visualization | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ymac344/CIS432/blob/main/notebooks/Homework-part1.ipynb) |
| 2 | Training and evaluating predictive models | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ymac344/CIS432/blob/main/notebooks/Homework-part2.ipynb) |
| 3 | Linear and tree-based models | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ymac344/CIS432/blob/main/notebooks/Homework-part3.ipynb) |

| test | Practice submission (automatic grading) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ymac344/CIS432/blob/main/notebooks/Test-assignment.ipynb) |

### How to work on an assignment

1. Click the **Open in Colab** badge. Colab opens the notebook in your Google account.
2. Choose **File → Save a copy in Drive** so your work is saved.
3. Run the first code cell. It downloads the data files and the answer key into your Colab session
   (you need to rerun it whenever the session restarts).
4. Answer the questions. Each question is followed by a test cell marked
   `### BEGIN TEST (DO NOT REMOVE CELL)`; run it to check your answer immediately.
   Do **not** edit or delete the test cells.
5. When you are done, choose **File → Download → Download .ipynb** and upload the
   file to the course site before the deadline.

Before submitting, it is a good idea to choose **Runtime → Restart session and run all**
and make sure the whole notebook runs from top to bottom without errors.

Working on your own computer instead of Colab is fine too: download the notebook and the files
listed in its first cell (folders `data/`, `answer_keys/`, `images/`) into one folder and open the
notebook in Jupyter. Use Python 3 with pandas, numpy, scikit-learn, matplotlib, seaborn and openpyxl.

### About the answer key

The objects you are asked to create are also provided in the variable `ANSWER_KEY` so you can
compare your results and debug. The answer key is for **debugging only**. Using it in your
submission or hard-coding answers is plagiarism and will be reported.

## Files

- `notebooks/` – the three homework notebooks
- `data/` – the HELOC dataset ([source](https://community.fico.com/s/explainable-machine-learning-challenge)),
  its data dictionary, and a preprocessed version used in part 3
- `answer_keys/` – precomputed answers used by the test cells; `versions.json` lists the
  library versions they were generated with
- `images/` – figures displayed in the notebooks
