# My Lesson Exercises

Keep personal notebooks, scripts, notes, and exercise results here. Use one
folder per lesson, mirroring its path in the curriculum:

```text
learning-artifacts/phases/<phase-directory>/<lesson-directory>/
```

For example, Phase 0, Lesson 5 lives in
`phases/00-setup-and-tooling/05-jupyter-notebooks/` inside this directory.
Keep each lesson's code and small input/output files together so relative
paths continue to work. Create folders as you reach new lessons.

In JupyterLab, navigate to the lesson folder before creating or opening a
notebook. If the notebook was already open when moved, close its old tab and
open it from its new location; restart the kernel and run all cells to use
the new working directory.

For scripts, run commands from the exercise folder when they use relative
file paths. The curriculum's reference implementations remain under the
repository's top-level `phases/` directory.

Lesson 5 contains `lesson-05-jupyter.ipynb` and `lesson-05-results.csv`.
