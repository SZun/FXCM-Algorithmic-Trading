# FXCM-Algorithmic-Trading
Multiple algorithmic trading strategies leveraging the FXCM brokerage API

## [Notebook Here](https://github.com/SZun/FXCM-Algorithmic-Trading/blob/main/FXCM-Algorithmic-Trading.ipynb)

## Images from Notebook

![](./assets/con.png)
![](./assets/sma.png)
![](./assets/boll.png)
![](./assets/ml.png)

## Getting Started

### Prerequisites

You must have anaconda and conda installed

```
$ anaconda --version
```
*# OUTPUT: "anaconda Command line client (version 1.11.0)"*
```
$ conda --verison
```
*# OUTPUT: "conda 22.9.0"*


### Installing

**Clone** the repo using SSH

```
$ git clone git@github.com:SZun/FXCM-Algorithmic-Trading
```

Then **cd** into the directory

```
$ cd FXCM-Algorithmic-Trading
```

Create the environment, add it to jupyter and launch jupyter lab

```
$ conda env create -f fxcm_env.yml
$ jupyter kernelspec remove ENVIRONMENT_1_NAME ENVIRONMENT_2_NAME
$ conda install -c conda-forge nb_conda_kernels -y
$ jupyter lab
```

## Built With

- [Scikit-Learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/docs/#)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/stable/index.html)
- [Fxcmpy](https://fxcmpy.tpq.io/00_quick_start.html)
- [Pickle](https://docs.python.org/3/library/pickle.html)
- [Datetime](https://docs.python.org/3/library/datetime.html)
- [Time](https://docs.python.org/3/library/time.html)

## Author

**Samuel Zun** 
- [LinkedIn](https://www.linkedin.com/in/szun/) | [Github](https://github.com/SZun)