# Boosting Climate Analysis with Semantically Uplifted Knowledge Graphs
With the spirit of reproducible research, this repository includes a complete collection of codes required to generate the results and diagrams presented in the paper:

> J. Wu, F. Orlandi, D. O'Sullivan, E. Pisoni, and S. Dev, Boosting Climate Analysis with Semantically Uplifted Knowledge Graphs, *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, 2022.

## Details
- `kg_sensor_analysis.ipynb` contains coding work for sensor selection determined by using the combination of [`Boruta`](https://pypi.org/project/BorutaShap/) algorithm and [`lazy_predict`](https://lazypredict.readthedocs.io/en/latest/), which is the first phase of the experiment on the paper.
- `kg_rainfall_detection.ipynb` contains machine learning performance comparisons on NOAA data with/without Link-Climate knowledge graph. The machine learning algorithms are taken from [`scikit-learn`](https://scikit-learn.org/stable/) and have been optimized for the rainfall detection task. The connection to Link-Climate is automated by employing [`kgextension`](https://kgextension.readthedocs.io/en/latest/). This part of coding work is the second phase of the experiment.
