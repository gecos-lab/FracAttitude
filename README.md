# FracAttitude

Jupyter Notebook for geological orientation analysis.

To run FracAttitude your conda environment must include [mplstereonet (plotting)](https://github.com/joferkington/mplstereonet/), [scikit-learn-extra (K-Medoids)](https://scikit-learn-extra.readthedocs.io/en/stable/generated/sklearn_extra.cluster.KMedoids.html#sklearn_extra.cluster.KMedoids), [sphstat (spherical stats)](https://sphstat.readthedocs.io/en/latest/index.html), and other usual libraries such as Numpy, Matplotlib, Pandas and Scipy.

To create a conda environment use:

`conda env create -n fracattitude -f ./fracattitude-env-from-history.yml`

Then switch to the new environment and install sphstat with PyPi:

```
conda activate fracattitude
pip install sphstat
```

To run a new analysis just clone the base notebook.

© 2024 Andrea Bistacchi, released under GNU AFFERO V.3 license.
