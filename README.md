# Boosting Climate Analysis with Semantically Uplifted Knowledge Graphs
With the spirit of reproducible research, this repository includes a complete collection of codes required to generate the results and diagrams presented in the paper:

> J. Wu, F. Orlandi, D. O'Sullivan, E. Pisoni, S. Dev, Boosting Climate Analysis with Semantically Uplifted Knowledge Graphs, *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, 2022.

## Details
- `kg_climate_analysis.ipynb` contains coding work for sensor selection determined by using the combination of [`Burota` algorithm](https://pypi.org/project/BorutaShap/) and [`lazy_predict`](https://lazypredict.readthedocs.io/en/latest/), which is the first phase of the experiment on the paper.
- `kg_rainfall_detection.ipynb` contains machine learning performance comparisons on NOAA data with/without Link-Climate knowledge graph. The machine learning algorithms are taken from [`scikit-learn`](https://scikit-learn.org/stable/) and have been optimized for the rainfall detection task. This part of codeing work is the second phase of the experiment.
