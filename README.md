# SB vs MB4

**Repository for the analysis and code supporting the article:**  
**"The 9-Minute Solution: Advancing Functional Connectivity Mapping with Multiband fMRI"**  
by Adrian Falkowski, PhD and Krzysztof Szwed, MD, PhD

## 📄 Abstract

This repository contains all the Python and R-based code used in the analysis of resting-state fMRI data comparing multiband (MB4) and single-band (SB) acquisitions.



## Requirements

Install dependencies via pip:

```bash
pip install -r requirements.txt
```

Additional requirements:

- **R (≥ 4.0)** with packages:
  - `lme4`
  - `lmerTest`
  - `car`

- **External tools**:
  - [`fMRIPrep`](https://fmriprep.org/)
  - [`AFNI`](https://afni.nimh.nih.gov/)
  - [`portrait-divergence`](https://github.com/bagrow/network-portrait-divergence) (for graph similarity analysis)

## Main Features

- **Portrait Divergence analysis** for reliability of functional connectomes
- Comparison of **SB vs MB4** rs-fMRI acquisition at multiple durations (5–13 min)
- Preprocessing with:
  - fMRIPrep (standardized anatomical registration)
  - AFNI 3dTproject (censoring, filtering, nuisance regression)

- Linear mixed-effects models with `rpy2` interface to R


## Citation

If you use this code or build upon it, please cite:

> TO DO

## License

License: CC-By Attribution 4.0 International
