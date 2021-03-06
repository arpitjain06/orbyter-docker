# manifoldai/orbyter-ml-dev:2.0

Dockerfile for [manifoldai/orbyter-ml-dev:2.0](https://hub.docker.com/r/manifoldai/orbyter-ml-dev)

## Usage

To run a bash shell

`
docker run -it manifoldai/orbyter-ml-dev:2.0 bash
`

## Release Notes:

Now using `orbyter-base-sys:2.0` as a base image. 

### Python package updates

#### Removed

cufflinks==0.16

#### Updated

streamlit==0.50.1
notebook==6.0.2

## Added

statsmodels==0.10.1

## Image overview

For a complete list all packages, run `pip freeze` in a container. Below is a summary of
the useful packages for ML development.

System:

* Ubuntu 18.04.3 LTS
* Python 3.7.5

## Included Packages :

* bayesian-optimization==1.0.1
* black==19.3b0
* bokeh==1.3.4
* boto3==1.9.233
* Click==7.0
* coloredlogs==10.0
* dask[complete]==2.4.0
* dask-ml==1.0.0
* dlib==19.17.0
* fire==0.2.1
* flake8==3.7.8
* ipdb==0.12.2
* isort==4.3.21
* jsonlines==1.2.0
* jupyter==1.0.0
* jupyter-contrib-nbextensions==0.5.1
* lightgbm==2.2.3
* matplotlib==3.1.1
* mlflow==1.2.0
* more-itertools==7.2.0
* notebook==6.0.2
* numpy==1.17.2
* pandas==0.25.1
* plotly==4.1.1
* pluggy==0.13.0
* psycopg2==2.8.3
* pyarrow==0.14.1
* pytest==5.1.3
* python-dotenv==0.10.1
* pytictoc==1.5.0
* scikit-learn==0.21.3
* scipy==1.3.1
* seaborn==0.9.0
* shap==0.30.1
* Sphinx==2.0.1
* statsmodels==0.10.1
* streamlit==0.50.1
* SQLAlchemy==1.3.2
* xarray==0.13.0
* xgboost==0.90
