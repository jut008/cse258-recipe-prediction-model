# CSE 258 Assignment 2

Group project for CSE 258 (Fall 2026).

## Files
- `workbook.ipynb`: the final notebook we submit (exported to `workbook.html`)
- `scratch/`: everyone's personal notebooks for experimenting
- `dataset/`: local data only, not committed (see below)

## How we work
Notebooks don't merge well in git, so:
1. Experiment in your own notebook in `scratch/` (e.g. `scratch/judy.ipynb`).
2. When something works, copy it into your section of `workbook.ipynb`.
3. Only one person edits `workbook.ipynb` at a time. Say so in the group chat first.
4. Always `git pull` before you start and `git push` when you're done.

## Data
Datasets are too big for GitHub. Download them into `data/` on your own machine
(or use the shared Drive folder in Colab). `data/` is in `.gitignore`.

Dataset: [name + link]

## Submitting
1. Restart and run all cells in `workbook.ipynb`
2. `jupyter nbconvert --to html workbook.ipynb --output workbook.html`
3. Upload `workbook.html` and `video_url.txt` to Gradescope
