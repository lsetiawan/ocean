# ocean

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/robfatland/ocean/HEAD)


### Purpose

This repository illustrates ocean data science. The code is Python broken up as topic
notebooks. Data courtesy of 
[OOI Regional Cabled Array](https://interactiveoceans.washington.edu), NASA, ARGO and other research programs.
To explore: Click on the binder badge above to launch a sandbox copy.
Typical start time will be about 3 minutes. Once binder
finishes try running the first notebook, ***Ocean 01 A Photic Zone***.
When you are done just close the browser tab and the sandbox will evaporate.




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
