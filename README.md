[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/axiom-data-science/SIWO/HEAD?labpath=notebooks%2Fsiwo_ice_animation.ipynb)

# SIWO
Animation of ice from HYCOM to support Sea Ice for Walrus Outlook. The animation is built by plotting frames of forecasts made available by [hycom.org](https://www.hycom.org/).

# How to Use

## Use with Binder

Click Binder badge above!

## Use locally

### Clone repository

``` bash
git clone git@github.com:axiom-data-science/SIWO.git
```

### Set up Python environment

If you don't already have conda or miniconda installed, download that first from here: https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html

Go to your local version of SIWO. Then:
``` bash
conda env create -f environment.yml
```

Then activate your new environment:
``` bash
conda activate SIWO
```


### Run the code!

Open the notebook:
``` bash
jupyter lab
```

JupyterLab will open in your web browser. You can navigate to the notebook in the "notebooks" directory.

Run the code in the notebook by pushing "shift" + "enter" on each cell.
