# Statistics labs

Four labs for **CMSE11624 Statistics for Analytics**, covering lecture weeks 1–9.

Use the supplied code to investigate statistical ideas: predict a result, run an
experiment, explain the evidence and state the assumptions. Each notebook contains
the activities, space for short responses and worked checks.

| Lab | Lecture weeks | Main questions | Notebook |
|---|---|---|---|
| 1 — From data to probability | 1–3 | Which data source fits the question? What do summaries and conditional probabilities tell us? | [Lab 1](Lab1/Lab1.ipynb) |
| 2 — Models, sampling and estimation | 4–5 | How does a model describe a process? Why do estimates vary, and what does confidence mean? | [Lab 2](Lab2/Lab2.ipynb) |
| 3 — Testing claims and comparing groups | 5–7 | Which comparison matches the design? What do a p-value, interval and power measure? | [Lab 3](Lab3/Lab3.ipynb) |
| 4 — ANOVA, correlation and regression | 8–9 | How do we compare several means, interpret adjusted relationships and evaluate predictions? | [Lab 4](Lab4/Lab4.ipynb) |

## Open a notebook

Download or clone the whole repository, retaining the folders and datasets. Use
Python 3.11 or newer. From this repository's root, install the packages and start JupyterLab:

```bash
python -m pip install -r requirements.txt
python -m jupyterlab
```

A virtual environment is recommended. Create one with `python -m venv .venv`,
then activate it using `source .venv/bin/activate` on macOS/Linux or
`.venv\Scripts\Activate.ps1` in Windows PowerShell before installing the packages.
On systems where the command is `python3`, use that in place of `python`.

**The university virtual machine (Noteable) is highly recommended!**

Open the relevant notebook and select the Python environment containing these
packages. Run cells from the top with **Shift+Enter**. Each notebook supports a
working directory of either its own folder or the repository root. After
installation, the calculations need no network access. Source links are for reading.

## Work through a lab

Work through the notebook's activities and exit task. Read each prediction or
discussion prompt before running the supplied cell, and write your interpretation
in the response cell. Double-click a response cell to edit it, then press
**Shift+Enter** to display your text. Worked checks are available in the same notebook. Optional
investigations after the exit task provide further practice.

Change one assumption or parameter at a time when experimenting. Use **Restart
Kernel and Run All Cells** to return to a complete, reproducible analysis.

For Python preparation (if you're not still not familiar with Python), use
[Python fundamentals](python-fundamentals/Python-fundamentals.ipynb). It covers
variables, collections, loops, functions, arrays, reading CSV/Excel, tables and
joins, with practice and worked checks in one notebook.

## Data

Each lab folder contains one notebook and only the datasets it uses. Data guides
inside the notebooks explain the observational units, variables, sources and
sampling assumptions. Simulations identify their generating models and seeds.

Labs 1–3 use selected columns from all 45,211 records in Moro, Rita and Cortez's
[UCI Bank Marketing dataset](https://doi.org/10.24432/C5K306), licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The accompanying
datasets support spatial-memory, office-time, process-monitoring, paired-media,
subscriber-survey, branch-rate and state-level regression examples.

