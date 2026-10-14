# AIDAMS Lab 3

This repository contains our completed notebook on bottom-up steel emissions and uncertainty. It uses the Global Iron and Steel Tracker plant-level workbook, June 2026 V1, in the `data/` folder.

## Run the notebook

Use Python 3.12 or newer. From this folder:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

Open `lab3.ipynb` in VS Code, select the Python interpreter in `.venv/bin/python` as the notebook kernel, then run all cells from the top. The notebook loads the included workbook by default. To use a different copy, set the `GIST_PATH` environment variable before starting the notebook.

The figures in the original questions were based on an older data release. Our answers use the June 2026 workbook.
