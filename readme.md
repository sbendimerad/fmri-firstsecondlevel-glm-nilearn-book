# fMRI First- and Second-Level GLM with Nilearn

This repository provides a **step-by-step tutorial** on statistical modeling of fMRI data using **Nilearn**, covering the full pipeline from **subject-level GLM** to **group-level (random-effects) inference**.

The tutorial is designed for students and researchers who want to **truly understand what is being estimated, why, and how to interpret the results**.

---

## What this tutorial covers

- fMRI first-level GLM (subject level)
- Design matrices and contrasts
- Effect size, variance, t-statistics, and z-statistics
- Subject-level t-maps and z-maps
- Second-level GLM (intercept-only group model)
- Group-level z-maps
- Multiple-comparison correction (FDR)
- Interpretation of red/blue activations and statistical maps
- Common pitfalls and misconceptions (e.g. z-map vs correction)

---

## Dataset

- **NARPS** (Neuroimaging Analysis Replication and Prediction Study)
- OpenNeuro dataset: `ds001734`
- Task: Mixed Gambles Task (MGT)
- Preprocessing: fMRIPrep (MNI space)
- Only two subjects are used for didactic purposes

⚠️ This tutorial is **educational**, not intended for scientific inference with N=2.

---

## Intended audience

- Students learning fMRI analysis
- Researchers transitioning to Nilearn
- Anyone who wants a **conceptual and computational understanding** of GLMs in neuroimaging

---

## Requirements

- Python ≥ 3.9
- Nilearn
- NumPy, Pandas, Matplotlib
- AWS CLI (for downloading OpenNeuro data)

---

## How to use

1. Clone the repository
2. Open the notebook in Jupyter
3. Run cells sequentially
4. Read the explanations alongside the code

---

## License

This tutorial uses open data and is provided for educational purposes.
