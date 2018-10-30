# GIS-EU

## Motivation

## Installation
It is highly recommended to create a anaconda environment to install the required packages and dependencies. Check out: [Ananconda Install](https://www.anaconda.com/download/) on instructions to install anaconda.
Check out [Anaconda Environment](https://conda.io/docs/user-guide/tasks/manage-environments.html) for creating and working with conda environement. 

Please clone the repository into a local folder. As this repository is under active development, and hence use of git vc is recommended to update the changes. Please feel free to contribute. The required packages are written in environment.yml file. You can change the name of the environment in the environment.yml file: To create the environment navigate to local folder and use:

```
conda create env -f  environment.yml
```

## Data
Data raster datafiles used in this package are not stored in this repository but provided seperately. --- insert information about downloading data ---

The downloaded data should be stored in the subfolder: 01_Data500 (update if changed).

| Parameter     | Processing    | Source    | License |
|-----------    |------------   |--------   |---------|
| Elevation     |               | European Environment Agency |         |
| Slope         |               | European Environment Agency |         |
| Land Quality  |               | European Environment Agency |
| Protected Areas|              |           |         |
| River Courses|                |Geofabrik|        |
| Population density|           |CIESIN; JRC           |         |
| Railways |               | Geofabrik          |         |
| Highways |               | Geofabrik          |         |
| Electricity Grid |               |           |         |

## Usage

The package code is divided into two jupyter notebooks:
- [Least Path](https://github.com/samarthiith/GIS-EU/blob/master/leastPath.ipynb)
    - This notebook is used for reading the raster data, combining them according to the factors considered and finally calculating the path. 
- [AnalysisOfPath](https://github.com/samarthiith/GIS-EU/blob/master/AnalysisOfPath.ipynb)
    - The paths created are analysed here. 

# License
This repository is published under [MIT License](https://github.com/samarthiith/GIS-EU/blob/master/LICENSE)
