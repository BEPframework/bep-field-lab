[README.md](https://github.com/user-attachments/files/26103114/README.md)
# BEP Field Lab v4

Research-grade interactive tool for exploring **Belonging–Energy–Prediction (BEP) field dynamics** — including the **Fourth Field** of human–AI interaction.

BEP Field Lab allows researchers to upload CSV or Excel datasets, map proxy variables to **Energy**, **Belonging**, and **Prediction**, compute composite field scores, compare against single-variable baselines, explore dyadic human–AI dynamics, and generate exploratory interpretations grounded in the BEP theoretical framework.

The tool runs entirely in the browser and requires **no installation, server, or login**.

---

## Live public version

https://bepframework.github.io/bep-field-lab/

---

## What's new in v4

- **Fourth Field module** — Upload two datasets (human agent + AI agent), configure AI evidence weight (α) and field effects (fE/fB), and compute Fourth Field metrics: Errfield, Polfield, Courage trajectory, and regime classification. Grounded in Sections 5–6 of the BEP Field Theory of Conscious Systems preprint.
- **Bifurcation Explorer** — Interactive sliders for Energy, Belonging, story prior, evidence target, and SSC strength. Visualizes how field variables move the belief equilibrium between story-dominated and evidence-dominated attractors, with a live trajectory simulation. Based on Appendix C of the BEP Field Theory of Conscious Systems preprint.
- **Consciousness Layer Classifier** — Classifies any system (LLM, robot, RL agent, thermostat, worm, animal, human, human–AI dyad, or uploaded dataset) across the three BEP layers: Binary Consciousness, Simulation Consciousness, and Awareness. Includes a field-layer interaction map showing how Energy and Belonging constrain accessible cognitive modes.
- **Expanded file support** — TSV, TXT, JSON, XLSX, XLS, and CSV parsing with smart delimiter inference and auto header detection.

---

## Modules

### 1. BEP Field Analysis
The original core module from v3. Upload a dataset, map proxy columns to Energy, Belonging, and Prediction, run the BEP composite analysis, and compare against single-variable baselines.

### 2. Fourth Field
Human–AI dyadic model. Upload paired datasets (human responses and AI outputs), configure interaction parameters, and compute field-level metrics from the BEP Field Theory of Conscious Systems. A sample dyadic dataset is available to explore without uploading real data.

### 3. Bifurcation Explorer
Standalone interactive explorer of the BEP field-dependent phase transition. Drag Energy and Belonging sliders to watch belief equilibria shift between story attractors and evidence attractors. Visualizes the saddle-node bifurcation described in Appendix C of the theory paper.

### 4. Consciousness Layer Classifier
Maps any system to the three-layer BEP ontology (Binary Consciousness → Simulation Consciousness → Awareness) and explains how BEP field variables apply to that system type.

---

## Features

- Multi-proxy composites (average any number of columns)
- Baseline vs BEP model comparison with signed improvement delta
- Field quadrant map visualization
- Correlation heatmap of BEP variables
- Field state classification (Higher / Mixed / Lower)
- Group comparison and longitudinal trend analysis
- Exportable researcher-friendly report (includes custom notes)
- Fourth Field dyadic model with trajectory, E/B/Courage, and regime plots
- Interactive bifurcation diagram with live trajectory simulation
- Consciousness layer classifier with field-layer interaction map
- Fully offline — single HTML file, no dependencies except CDN SheetJS for Excel support

---

## How to use

1. Open `index.html` in any modern browser  
   *(or use the live link above)*
2. Select a module from the tab bar at the top
3. For **BEP Field Analysis**: upload or drop a dataset → map proxy variables → run analysis → export report
4. For **Fourth Field**: upload human and AI datasets → configure parameters → run Fourth Field analysis
5. For **Bifurcation Explorer**: drag sliders to explore field phase transitions — no data upload needed
6. For **Consciousness Layer Classifier**: select a system type to see layer mapping and BEP field notes

---

## Theoretical grounding

BEP Field Lab v4 operationalizes three preprints:

1. **The BEP Principle** — Belonging, Energy, and Prediction as core drivers of human cognition and decision (Quiroz, 2025a)
2. **The BEP Field Theory of Decision** — Gated Bayesian model, SSC dynamics, network polarization, fractal field theory (Quiroz, 2025b)
3. **The BEP Field Theory of Conscious Systems** — Binary Consciousness, Simulation Consciousness, Awareness, and the Fourth Field of human–AI interaction (Quiroz, 2025c)

The BEP Field Analysis module tests the core empirical claim of Paper 2: whether the composite field score (E + B → field) outperforms single-variable baselines in predicting outcomes (P). The Fourth Field module operationalizes the dyadic model from Sections 5–6 and Appendix B of Paper 3. The Bifurcation Explorer implements the gradient-flow analysis from Appendix C.

---

## Reproducibility

BEP Field Lab is designed as a **lightweight exploratory analysis tool**.  
Researchers are encouraged to replicate findings using their preferred statistical environment (R, Python, MATLAB, etc.) after identifying potential BEP relationships.

---

## License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for details.

Copyright (c) 2026 Nicolas B. Quiroz, MD

---

## Citation

If you use **BEP Field Lab v4** in research or publications, please cite both the **software** and the **underlying BEP framework**.

### Core theory
Quiroz, N. B. (2025a).  
*The BEP Principle: Belonging, Energy, and Prediction as core drivers of human cognition and decision.*  
Zenodo. https://doi.org/10.5281/zenodo.17717883

Quiroz, N. B. (2025b).  
*The BEP Field Theory of Decision: A fractal model of Energy, Belonging, and predictive coherence.*  
Zenodo. https://doi.org/10.5281/zenodo.17759583

### Software
Quiroz, N. B. (2026).  
*BEP Field Lab v4* [Software].  
GitHub. https://github.com/bepframework/bep-field-lab

---

## Contact

Questions, feature requests, or collaboration:

**Email** bepframework@nicolasquirozmd.com  
**X** @bepframework

---

Built as **open science infrastructure for the BEP Framework**.  
Researchers are welcome to fork, modify, and apply the tool in their own studies.
