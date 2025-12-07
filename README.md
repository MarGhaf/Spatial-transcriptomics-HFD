# Spatial-transcriptomics
# Spatial Transcriptomics of High-Fat Diet–Altered Apical Periodontitis

This repository contains analysis code and notebooks for a spatial in situ single-cell transcriptomics study of apical periodontitis (AP) in mice under normal chow (NC) and high-fat diet (HFD) conditions. The analyses use 10x Genomics Xenium FFPE data to characterize how chronic dietary fat reshapes neutrophil and macrophage states and periapical tissue programs at the root–bone interface.

## Repository Contents

- `Control_HFD_vs_NC.ipynb`  
  Analysis notebook for **non-lesion (control) periapical tissues**, comparing:
  - HFD vs NC controls
  - Baseline neutrophil and macrophage transcriptional states
  - Gene Ontology (GO:BP) enrichment for diet-driven metabolic and immune shifts

- `AP_HFD_vs_NC.ipynb`  
  Analysis notebook for **apical periodontitis (AP) lesions**, comparing:
  - AP HFD vs AP NC
  - Diet-specific neutrophil and macrophage clusters in lesions
  - GO:BP enrichment for foam-cell–like, lipid-handling, and antimicrobial programs



## Data

- **Platform:** 10x Genomics Xenium, FFPE, mouse periapical tissues  
- **Panel:** Mouse Tissue Atlassing panel (~379 genes)  
- **Samples:** NC vs HFD, control vs AP, maxillary/mandibular periapical regions  
- **Raw data:** cell_feature_matrix.h5



## Environment and Dependencies

The analyses were run in Python using a standard single-cell / spatial transcriptomics stack:

- `python` ≥ 3.9
- `scanpy`
- `squidpy`
- `harmonypy`
- `spatialdata`
- `scikit-misc`
- `gseapy`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `anndata`
- `scikit-learn`
- `statsmodels` (optional, for some statistical summaries)
- `graphviz` / `python-igraph` (optional, depending on plots)


