# Analysis of Fentanyl samples

[![DOI](https://zenodo.org/badge/298631447.svg)](https://zenodo.org/badge/latestdoi/298631447)

This work is accompanying a publication in [Forensic Chemistry](https://doi.org/10.1016/j.forc.2021.100330).

In this analysis, we try to differentiate between different synthesis routes for fentanyl. The samples were analyzed 4 years after the synthesis. They were stored both at -20 and at room temperature (RT). All the samples were also analyzed after incubation with liver microsomes. This mimics the process that occurs in the body if someone is exposed to fentanyl. The samples were measured with four chromatographic techniques: GC-MS, GC-FID, LC-MS Maxis and LC-MS Orbitrap.

## Data
The data is not made publicly available due to safety considerations.
The identifiers of the different impurities mentioned in the paper and used throughout the scripts are stored in [header.csv](./header.csv).

## Installation
Download Jupyter Notebook per instructions on https://gerritjandebruin.nl/jupyter.html.
Then install the following environment:
```bash
conda create -y -n impurityProfiling python=3.7.6 pandas scipy scikit-learn seaborn jupyter jupyter_contrib_nbextensions
conda activate impurityProfiling
jupyter nbextension enable toc2/main
```

## Contributing
The chromatographic analyses were performed by [Mirjam de Bruin](https://forensicscientist.nl) while the analysis of the data was carried out by [Gerrit-Jan de Bruin](https://gerritjandebruin.nl) and [Mirjam de Bruin](https://forensicscientist.nl).
