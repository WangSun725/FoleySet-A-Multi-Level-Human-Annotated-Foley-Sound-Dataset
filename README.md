# FoleySet: A Multi-Level Human-Annotated Foley Sound Dataset

This repository accompanies **FoleySet**, a multi-level human-annotated Foley sound dataset.

The repository contains the benchmark code, metadata, and evaluation materials used in the accompanying paper.

---

## Paper

For a detailed description of the dataset construction, annotation protocol, benchmark experiments, and analysis, please refer to:

**FoleySet: A Multi-Level Human-Annotated Foley Sound Dataset**

**Paper:**  
https://arxiv.org/pdf/2606.25980

---

## Dataset

The complete audio dataset is publicly available on Zenodo:

**Dataset:**  
https://zenodo.org/records/20735877

The dataset contains:

- **10,000** human-annotated Foley audio clips
- Hierarchical annotations with both **major** and **sub-category** labels
- Curated metadata for benchmark evaluation
- Standard train/test splits used in the paper

---

## Repository Overview

This repository provides:

- Dataset metadata
- Benchmark classification scripts
- Evaluation results
- Example code for reproducing the baseline experiments

---

## Repository Structure

```text
.
├── README.md
├── metadata/
│   └── metadata.csv
├── benchmark/
│   ├── benchmark_classification.py
│   ├── passt_major_result/
│   └── passt_sub_result/
```

---

## Requirements

- Python 3.10+
- NumPy
- Pandas
- PyTorch
- torchaudio

Additional dependencies may be required depending on the benchmark model.

---

## Benchmark

The provided benchmark includes baseline audio classification experiments for both:

- Major-category classification
- Sub-category classification

The benchmark scripts can be adapted for training and evaluating additional audio representation models.

---


## Supplementary Tables

Complete supporting tables accompanying the FoleySet paper are available here:

- [Keyword-to-category mapping](supplementary/keyword_to_category_mapping.md)
  ([CSV](supplementary/keyword_to_category_mapping.csv))
- [Full 73-class sub-category classification results](supplementary/subcategory_classification_results.md)
  ([CSV](supplementary/subcategory_classification_results.csv))

These files provide both human-readable and machine-readable versions of the complete taxonomy mapping and per-class benchmark results.

---

## Citation

If you use FoleySet in your research, please consider citing:

```bibtex
@article{wang2026foleyset,
title={FoleySet: A Multi-Level Human-Annotated Foley Sound Dataset},
author={Wang, Sunshiyu and Lerch, Alexander},
journal={arXiv preprint arXiv:2606.25980},
year={2026}
}
```


---

## License

The dataset and accompanying code are provided for academic research purposes. Please refer to the dataset license on Zenodo for usage terms.
