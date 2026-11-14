# ECG Signal Processing and Simulated Acquisition

## Purpose
Develop practical biomedical engineering skills through an educational,
reproducible project documented on GitHub.

## Version 1 — Python ECG processing
Input:
- Recorded ECG signals from the MIT-BIH Arrhythmia Database.
- Reference beat annotations used for evaluation.

Functions:
- Load and inspect ECG recordings.
- Display waveforms and frequency spectra.
- Apply and assess filtering.
- Detect R-peaks.
- Calculate RR intervals and heart rate.
- Evaluate beat detection against reference annotations.

Outputs:
- Jupyter notebooks and reusable Python functions.
- ECG figures and measurement plots.
- Performance tables and failure analysis.
- Reproduction instructions and documented limitations.

## Validation plan
- Use separate recordings for development and final evaluation.
- Define reference beat types and a one-to-one matching tolerance.
- Report sensitivity, positive predictive value, F1 score,
  and timing error for matched beats.
- Evaluate at least ten recordings as an initial milestone.
- Inspect failures and report results without inventing performance targets.

## Version 2 — Simulated acquisition and electronics
- Model gain, offset, sampling, ADC quantization, and clipping in Python.
- Simulate an analog signal-conditioning circuit in LTspice.
- Document assumptions and compare simulated outputs.

## Version 3 — STM32 extension
- Target STM32F401RE using STM32CubeIDE.
- Port selected processing functions into C.
- Compare C outputs with the Python reference.
- Distinguish compilation, host testing, simulation, and hardware verification.

## Boundaries
- Educational project; no clinical diagnostic claims.
- No hardware purchase required for Version 1.
- Beat classification is a possible later extension.
- Physical acquisition is outside the initial scope.

## Working method
- Progress one verified action at a time.
- Explain code and results.
- Keep an Obsidian note after each action.
- Record coherent progress with Git.

## Current status
Initial setup is in progress. The Python environment works in Jupyter,
project folders exist, and the environment specification has been exported.
ECG processing has not started.
