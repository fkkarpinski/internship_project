# Internship project

Code, analysis, and notes for the scientific project.

## Layout

```text
data/        Local input and intermediate data (ignored by Git)
notebooks/   Exploratory analysis and experiment notes
results/     Generated figures and tables (ignored by Git)
src/         Reusable Python code in internship_project/
```

Keep the structure flat until there is a reason to add a folder. Add tests,
reference files, or other directories when they have actual content.

## Working on the project

Install the environment with `uv sync`, then start notebooks with
`uv run jupyter lab`. Put reusable functions in `src/internship_project/`
and import them from notebooks.

Use descriptive notebook names, such as `01_exploration.ipynb`. Record the
question, data source, method, and conclusions in each notebook. Keep source
data unchanged and give intermediate files distinct names in `data/`.

Data and generated results stay local; only their empty folder placeholders
are tracked. Record download links, preparation steps, and relevant paper
links here so someone else can reproduce the analysis.

## Project notes

- Research question: to be defined.
- Data sources and preparation: to be documented.
- References: add links as needed.
