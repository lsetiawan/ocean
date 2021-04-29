# ocean

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/robfatland/ocean/HEAD)


### Purpose

This repository illustrates ocean data science machinery. Code is in Python, broken up into topic
notebooks. Data are provided by the 
[OOI Regional Cabled Array](https://interactiveoceans.washington.edu) and other research programs.
To explore: Click on the binder badge above; typical start-up time is 3 minutes.




### How was this repository binder-ized?

Three steps

- Reduce the source data for the demo notebook down to a few MB so it "lives" in the repo folder
- Add the subfolder `binder` and the `environment.yml` file given below
- Add the binder badge linking to this repo

Badge code: 

```
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/robfatland/ocean/HEAD)
```


`binder/environment.yml` file: 


```
channels:
  - conda-forge
dependencies:
  - python=3
  - numpy
  - pandas
  - matplotlib
  - netcdf4
  - xarray
```
