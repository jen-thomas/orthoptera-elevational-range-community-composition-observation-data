# Investigating the relationship of elevation and Orthoptera species richness, elevational range and community composition: observation data and metadata.

This repository contains the observations of Orthoptera and associated metadata, which were collected as part of a project to investigate the relationship between elevation and the elevational range over which Orthoptera are found, in the Pyrenees.

These data were originally entered using a [Python / Django application](https://github.com/jen-thomas/wildlife-observations/releases/tag/v0.0.1) and stored in a MySQL database. They were [analysed using _R_](https://github.com/jen-thomas/orthoptera-elevational-range-community-composition). The final publication which uses these data will be available shortly.  

The initial release of this dataset is available on Zenodo with the DOI: [10.5281/zenodo.7763503](https://doi.org/10.5281/zenodo.7763503).

## Data files

* ```observations.csv``` contains all sightings of Orthoptera. 
* ```sites.csv``` contains the metadata about each of the sites at which Orthoptera were sighted.
* ```surveys.csv``` contains metadata about each of the surveys.
* ```vegetation_plots.csv``` contains data from the vegetation surveys which were undertaken at each site.

## Frictionless data package

This repository contains a data package, which consists of the four data files plus a machine-readable description of these files, ```schema_package.json```. The Frictionless website has a description of the structure and meaning of the [Frictionless Data Package schema](https://specs.frictionlessdata.io/guides/data-package/) and [how to work with it](https://framework.frictionlessdata.io). 

```describe_data_files.py``` creates the Frictionless Data Package and describes it, using the [Frictionless Framework tools](https://framework.frictionlessdata.io). The packages that are required to run this file are listed in ```requirements.txt```. 

## Data description

```data_file_descriptions.txt``` contains a plain text description of the fields in the data files. For more detailed descriptions of the field type and constraints, for example, see ```schema_package.JSON```.