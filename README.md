# S-index Hub: Resources, Code, and Data

This repo is a catalog of S-index project outputs: code repositories, released datasets, and materials needed to reproduce results. We will keep this updated as we keep working on this project. 

## Quick links
- 📘 S-index overview: [github.com/data-S-index/overview](https://github.com/data-S-index/overview)
- 🌐 Scholar Data web app: [beta.scholardata.io](beta.scholardata.io)
- 👩🏻‍💻 All code: [github.com/data-s-index](https://github.com/data-s-index)
- 🗃️ Data and code archival (Zenodo): [zenodo.org/communities/s-index](https://zenodo.org/communities/s-index/)
- 🗂️ Full catalog: see below
- 💬 Questions: [GitHub Issue](https://github.com/data-S-index/hub/issues) or bvhpatel@gmail.com
- 🔗 Cite this work: Coming soon

## Catalog

### Documentation

| Resource | Type | What it contains | Status | Latest | License | 
|---|---|---|---|---|---|
| [Overview](https://github.com/data-S-index/overview)| Documentation | Details about the S-index formulation and calculation | Stable | v1.0.0 | CC-BY |

### Code

| Resource | Type | What it contains | Status | Latest | License | 
|---|---|---|---|---|---|
| [S-index Parameters Analysis](https://github.com/data-S-index/s-index-parameters-analysis)| Code | Jupyter notebook used to analyze how different parameters influence the S-index to support our design choice | Stable | v1.0.0 | MIT |
| [S-index Real-World Testing and Validation](https://github.com/data-S-index/s-index-real-world)| Code | Jupyter notebook used to analyze the results of processing 49M+ datasets and calculating the S-index of 1M+ researchers | Stable | v1.0.0 | MIT |
| [Sindex Data Collection Pipeline](https://github.com/data-S-index/s-index-pipeline)| Code | Python code and Jupyter notebooks developed to collect dataset metadata, calculate FAIR scores, find citations, identify mentions, assign research field, and calculate S-index for our large scale testing with 49M+ datasets (and counting). A summary of the results is also included. | Stable | In continous development | MIT | 
| [Research field assignment model](https://github.com/data-S-index/dataset-to-field)| Code | Code for the custom fine-tuned model we developed to assign research fields to datasets based on their metadata using the OpenAlex Topics taxonomy | Stable | v1.0.0 | MIT | 
| [F-UJI fork](https://github.com/data-S-index/fuji)| Code | Fork of the F-UJI repository where we adapted the code for large scale usage | Stable | N/A | MIT |
| [Scholar Data app](https://github.com/data-S-index/web-app)| Code | Code of the Scholar Data web app (beta.scholardata.io) | Stable | In continous development | MIT | 
| [Scholar Data dev](https://github.com/data-S-index/dev-pipeline)| Code | Development pipeline for the Scholar Data app | Stable | In continous development | MIT | 
| [S-index API](https://github.com/data-S-index/s-index-api)| Code | API linking to our Dataset Registry | In continous development | In continous development | MIT |

### Data
| Resource | Type | What it contains | Status | Latest | License|
|---|---|---|---|---|---
| [S-index Real-World Testing and Validation Dataset](https://doi.org/10.5281/zenodo.18628067)| Dataset | Dataset metadata, FAIR scores, citations, mentions, and research field data collected/generated during our real world testing and validation of the S-index (NDJON format files)| Stable | v1.0.0 | CC0 |
| [S-index Real-World Testing and Validation DB Data](https://doi.org/10.5281/zenodo.18629105)| Dataset | A DuckDB database file with all the data collected plus Dataset Index and S-index calculated as part of our real world validation. This database is needed for the real world analysis Jupyter notebook. | Stable | v1.0.0 | CC0 |



