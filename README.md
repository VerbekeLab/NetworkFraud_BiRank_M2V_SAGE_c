# Network Analytics for Insurance Fraud Detection - A Critical Case Study </br><sub><sub> Bruno Deprez, Félix Vandervorst, Wouter Verbeke, Tim Verdonck, Bart Baesens [[2024]](https://link.springer.com/article/10.1007/s13385-024-00384-6)</sub></sub>

The source code of the experimental evaluation of the paper Deprez et al. (2024) - Network Analytics for Insurance Fraud Detection -- A Critical Case Study.

It provides an implementation of different network learning techniques applied in the experiments presented in the paper.

## Data
The main experiment is done on propietary data and healthcare provider data available on kaggle. 

This repository does not provide any data, due to size constraints. The data can be found online using the following links:
- [Health](https://www.kaggle.com/datasets/rohitrox/healthcare-provider-fraud-detection-analysis)

## Repository structure
The structure includes folders and scripts containing code. The files with results, i.e., csv-files, are not shown.
This repository is organised as follows:
```bash
.
├── Centralities/
│   ├── Centralities_1.csv
│   ├── Centralities.csv
├── Demo/
├── figures/
├── scripts/
│   ├── Centralities.py
│   ├── execute.py
│   ├── main.py
├── src/
│   ├── BiRank.py
│   ├── GraphSAGE_impl.py
│   ├── HelperFunctions.py
│   ├── metapath2vec.py
│   ├── Metrics.py
```

## Installing
We have provided a `requirements.txt` file:
```bash
pip install -r requirements.txt
```
Please use the above in a newly created virtual environment to avoid clashing dependencies.

## Citing
Please cite our paper and/or code as follows:

```tex


@article{deprez2024network,
  author = {Deprez, Bruno and Vandervorst, Félix and Verbeke, Wouter and Verdonck, Tim and Baesens, Bart},
  title = {Network analytics for insurance fraud detection: a critical case study},
  journal = {European Actuarial Journal},
  volume = {14},
  number = {3},
  pages = {965--990},
  year = {2024},
  doi = {10.1007/s13385-024-00384-6},
  url = {https://doi.org/10.1007/s13385-024-00384-6}
}
```

