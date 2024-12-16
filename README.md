# EarthObservation_and_tws

<!-- #region -->
# Preparation on the crib platform

To run the tutorioals you need the [shxarray software](https://github.com/ITC-Water-Resources/shxarray). We've prepared an installation in a so called Python virtual environment (`pysh_aarch64`,..). 

In order to make this virtual environment available for you when creating notebooks, you still need to do some steps

1. Clone this repository
```sh
git clone git@github.com:SedighehKarimi/EarthObservation_and_tws.git
```

2. From the Jupyter interface open a terminal File-> New -> Terminal
3. In the terminal window, navigate to the shared
```sh
cd /path/to/shared/directory
```

<!-- #endregion -->

## Setup the Virtual Environment:

<!-- #region -->


### Activate the virtual environment:
```sh
source /path/to/pysh_aarch64/bin/activate
```
<!-- #endregion -->

```
EarthObservation_and_tws
│   └───data # data folder
│    └───basins
│       │  AMAZONAS.gpkg
│       │   ...
│       │   GREENLAND.gpkg
│       │   ...
│   README.md
│   requirements.txt
│   setup.pipenv.sh
│   Tutorial_1_nocode.ipynb
│   Tutorial_1.ipynb
│   Tutorial_2.ipynb
```
