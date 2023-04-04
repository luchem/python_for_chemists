[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/luchem/python_for_chemists.git/master)

# Python for Chemistry Course

To run this on a remote Jupyter server, click _launch binder_ above.

## Usage (MacOS / Linux)

To open the Notebooks, install python via [Miniforge](https://github.com/conda-forge/miniforge) and
make sure all required packages are loaded by issuing the following terminal commands

``` bash
    conda env create -f environment.yml
    conda activate luchem
    jupyter nbextension enable rubberband/main
    jupyter nbextension enable exercise2/main
    jupyter nbextension enable --py widgetsnbextension
    jupyter-lab
```
