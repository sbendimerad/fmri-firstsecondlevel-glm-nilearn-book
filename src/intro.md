## 📘 fMRI First- and Second-Level GLM with Nilearn

This repository contains **Jupyter Book–style tutorials** on **statistical modeling of fMRI data** using the [`nilearn`](https://nilearn.github.io/) library.
The tutorials introduce the fundamentals of **General Linear Models (GLMs)** for fMRI, covering both **first-level (subject-level) analysis** and **second-level (group-level) inference**.

The focus is on developing a **conceptual and computational understanding** of how fMRI effects are estimated, standardized, combined across subjects, and statistically tested.
All examples are illustrated using the **open NARPS dataset (ds001734)** and follow a **step-by-step, transparent workflow**.

---

## Tutorial Contents

This series covers:

* **An introduction to fMRI GLMs and design matrices**
* **First-level (subject-level) modeling of fMRI time series**
* **Contrast estimation, effect sizes, variance, t-statistics, and z-statistics**
* **Interpretation of subject-level t-maps and z-maps**
* **Second-level (group) GLM using an intercept-only model**
* **Population-level inference and inter-subject variability**
* **Multiple-comparison correction using False Discovery Rate (FDR)**
* **Common misconceptions (e.g. z-maps vs statistical correction)**

Each notebook provides **theoretical intuition, practical implementation, and detailed guidance on how to interpret statistical maps**, with particular emphasis on *what is estimated, what is treated as noise, and why*.

---

## Dataset and scope

* **Dataset**: NARPS (Neuroimaging Analysis Replication and Prediction Study)
* **OpenNeuro ID**: `ds001734`
* **Task**: Mixed Gambles Task (MGT)
* **Preprocessing**: fMRIPrep (MNI space)
* **Subjects**: Restricted to two subjects for didactic clarity

⚠️ These tutorials are **educational** and not intended to draw scientific conclusions from small sample sizes.



