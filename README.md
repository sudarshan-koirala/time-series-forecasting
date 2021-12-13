# time-series-forecasting
Exploring different projects related to time-series prediction/forecasting

## Creating environment and installing packages
Assuming you have python and pip installed

1. Install virtual environment -> `pip3 install virtualenv`
2. Create the virtual env -> `virtualenv forecast / python3 -m virtualenv forecast`
3. Activate the virutal env -> `source forecast/bin/activate`
4. Install all the packages -> `pip3 install -r requirements.txt`
5. Run jupyterlab -> `jupyter lab`

## In some of the case, having conda environment is better
Assuming you have anaconda installed

1. Create conda environment -> `conda create -n forecast python=3.8`
2. Activate the conda env -> `source/conda activate forecast`
3. Install all the packages -> `pip/pip3 install -r requirements.txt`
4. Run jupyterlab -> `jupyter lab`

### Types of sensor data
```
Live Data: I want to know when something is not working.
Historical Data: I want to keep logs of when something has and has not been working.
Analytical Data: I want to understand why something isn’t working.
Predictive Data: I want to know when something will stop working.
Data for Change: I want to change how something works.
```
