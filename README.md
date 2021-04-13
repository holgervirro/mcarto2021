# Mathematical Cartography 2021
These Jupyter notebooks support the <b> Mathematical Cartography LOOM.02.007 </b> MSc course and focus on the capabilities of the Python mathematical cartography and visualization library [Cartopy](https://scitools.org.uk/cartopy/docs/latest/).

The first tutorial gives an overview of creating a map window, using projections and constructing basic map elements (grid, text)
* https://github.com/holgervirro/mcarto2021/blob/master/Kaardiakna_juhtimine.ipynb (Estonian version)
* https://github.com/holgervirro/mcarto2021/blob/master/Map_Window_Management.ipynb (English version)

The second tutorial focuses on additional map elements, such as point symbols and different cartographic line objects (orthodrome, rhumb line, almucantar)
* https://github.com/holgervirro/mcarto2021/blob/master/Kaardielemendid.ipynb (Estonian version)
* https://github.com/holgervirro/mcarto2021/blob/master/Map_Elements.ipynb (English version)

## Preparation
We will use [Anaconda](https://conda.io/en/master/miniconda.html) for these exercises, which should already be installed in the computer class. For setting it up on your own machine you can use the [tutorial](https://kodu.ut.ee/~kmoch/geopython2020/L0/Installing_Miniconda_GIS.html) provided by Alex Kmoch.

First, download and unzip this repository into a folder you can find on your machine.

*Clone or download -> Download ZIP*

Find and launch the Anaconda Prompt using the search bar.

We will start by creating an Anaconda environment using the existing environment file `mcarto2021_env.yml`, which installs all Python libraries needed for the two exercises.

`conda env create -f mcarto2021_env.yml`

The next command will activate the Anaconda environment we just created.

`activate mcarto2021`

Now move to the folder where you unzipped the GitHub repository.

`cd C:\Users\Holger\mcarto2021-master\mcarto2021-master`

Before we start Python coding we will make our newly created conda Python environment known to the Jupyter notebook system by installing the kernel, basically the execution engine link from Jupyter web notebook to our Python environment.

`python -m ipykernel install --user --name mcarto2021`

Finally, we can activate the Jupyter environment.

`jupyter lab`

A browser window will open where clicking on a Jupyter notebook file with the extension *.ipynb* allows you to start editing the notebook.

Click the Binder icon below to launch the tutorial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/holgervirro/mcarto2021/HEAD)
