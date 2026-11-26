# ECG Signal Processing and Simulated Acquisition

An educational biomedical engineering project developed step by step
with Python, JupyterLab, and documented validation.

## Objective

Build a reproducible workflow to inspect recorded ECG signals, assess
filtering, detect R-peaks, calculate RR intervals and heart rate,
and evaluate detections against reference annotations.

## Tools

- Python and JupyterLab
- NumPy, SciPy, and Matplotlib
- WFDB
- MIT-BIH Arrhythmia Database — planned data source

## Project structure

- `notebooks/`: exploratory notebooks and explanations
- `data/raw/`: original downloaded ECG files
- `results/figures/`: generated plots
- `results/tables/`: evaluation tables
- `docs/`: project specification, methods, and limitations
- `src/`: reusable Python functions

## Environment

The current environment is recorded in `environment.yml`.

## Roadmap

1. Inspect ECG recordings and annotations.
2. Explore noise and filtering.
3. Detect R-peaks and calculate heart rate.
4. Validate across multiple recordings.
5. Model signal acquisition and simulate analog electronics.
6. Develop selected processing functions for STM32.

See [the project specification](docs/project_specification.md)
for the planned scope and validation approach.

## Limitations

This is an educational project, not a clinically validated medical device.
Circuit simulation and STM32 firmware are planned extensions.
