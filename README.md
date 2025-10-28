# 2503.14584-data
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17463824.svg)](https://doi.org/10.5281/zenodo.17463824)

This repository contains complementary data for the paper: "Search for dark matter subhalos among unassociated Fermi-LAT sources in presence of dataset shift", [arXiv:2503.14584](https://arxiv.org/abs/2503.14584).

# Content of the tables

- `astro_probabilities_E0_1GeV.csv`: Contains the astrophysical class probabilities for the 4FGL sources within the Region of Interest (ROI) considered in our analysis. These posterior probabilities were derived using the "astro-only" model, trained on the unassociated 4FGL-DR4 source catalog.

- `DM_probabilities_{mDM}GeV.csv`: These files provide the posterior probabilities for 4FGL sources in the ROI to be Dark Matter (DM) candidates. Each file corresponds to a specific DM model, defined by a given DM mass ($m_{DM}$) and annihilation cross-section ($\langle \sigma v \rangle$), as specified in the filename. The probabilities are derived from our best-fit models for each DM hypothesis. 

> [!IMPORTANT]
> The DM probabilities are not the absolute likelihood of a source being DM. They represent conditional posterior probabilities. A probability $P(\text{DM} | \text{data})$ is calculated given the assumption that a specific DM model (defined by $m_{DM}$ and $\langle \sigma v \rangle$) is the true one.
> Therefore, a high probability (e.g., p_DM = 68%) should be interpreted as: "This source is a strong candidate for being a DM subhalo if the true DM particle has these specific properties." It does not imply the source is a 68% certain DM detection in an absolute sense.

# Citation

If you use the results from this work, please include the following citation:

```bibtex
@misc{amerio2025searchdarkmattersubhalos,
      title={Search for dark matter subhalos among unassociated Fermi-LAT sources in presence of dataset shift}, 
      author={Aurelio Amerio and Dmitry Malyshev and Bryan Zaldivar and Viviana Gammaldi and Miguel Ángel Sánchez-Conde},
      year={2025},
      eprint={2503.14584},
      archivePrefix={arXiv},
      primaryClass={astro-ph.HE},
      url={https://arxiv.org/abs/2503.14584}, 
}
```
