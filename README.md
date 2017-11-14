## Collection of Jupyter notebooks

To view notebooks online visit [nbviewer](http://nbviewer.jupyter.org/github/trichter/notebooks/tree/master/notebooks/).

If you want to run notebooks locally, please first install the following packages: `obspy obspyh5 tqdm rf yam`.
The easiest way to install the dependencies is via [anaconda](https://conda.io/miniconda.html):

```
conda create -n notebooks python=3 obspy h5py tqdm cartopy geographiclib shapely gcc
(source) activate notebooks
pip install obspyh5 rf yam
```

After that, clone the notebooks repository or download individual notebooks.
Navigate to the folder of the repository and run `jupyter notebook` to play with the code and the data.
A `data` folder has to be created in that directory.
