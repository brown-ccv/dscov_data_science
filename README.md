# DSCOV talks
This repository contains materials presented at the DSCOV seminar series in 2020. 

## Prerequistes

Please run check_env.ipynb. It checks the versions of your python and some packages (like pandas, sklearn, xgboost). If the notebook returns all OK, you should be able to run my notebooks without issues. If some FAILs are returned, you need to install/update those packages first. A conda environment file is provided to ensure reproducability (dscov_env.yml). To create and activate the environment,
please give the following commands in your terminal from the location of the yml file:

`conda env create -n dscov_env -f dscov_env.yml`

`conda activate dscov_env`

Once the environment is activated, you can launch jupyter-notebook from the terminal:

`jupyter-notebook` 

and now check_env.ipynb should give the all clear.

## Description

There is one folder per presentation and the folder name starts with the date of the presentation. Each folder contains one notebook and additionally a 'data', 'images', etc., folders as needed. The notebooks are also available in pdf format for convenience.

## Authors

Andras Zsom (andras_zsom@brown.edu).

## License

This project is licensed under the MIT License.
