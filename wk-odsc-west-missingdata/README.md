# ODSC West 2023 Workshop 
# Missing Data | A synthetic data approach to time-series missing data imputation

## Missing data in time-series
Time-series data is a type of data in which observations are collected or recorded over a sequence
of time intervals. These data can be used to analyze and understand how a particular variable changes over time,
such as stock prices, temperature measurements, or sales figures. 
However, time-series data often suffer from missing values, which are data points that are absent or unavailable
for some time intervals. 
Understanding and dealing with missing data in time-series analysis is crucial because it 
can have a significant impact on the quality of your analysis and forecasts.

In this workshop we will be able to:
- Profile and understand time-series missing data behaviour
- What are pros & cons of the different imputation mechanisms
- How can synthetic data boost time-series missing data imputation

### Dataset

The dataset used for this workshop is stocks from X and can be found here 
the IEEE-Fraud Detection can be found in [Kaggle](https://www.kaggle.com/c/ieee-fraud-detection).

### Requirements
This workshop/tutorial covers the following steps:
- Data Profiling for Time-series data
- Data Imputation mechanism
- Synthetic data imputation for time-series
- Data pipelines & orchestration with YData Fabric

What you will need: 
- Install in your local machine the required packages using the environment.yaml file
- Register at [YData Fabric](ydata.ai/register) to start exploring data pipelines

## Quickstart

### Conda environment

#### Prerequisites

- [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) (it can either be installed with [miniconda](https://docs.conda.io/en/latest/miniconda.html) or [anaconda](https://www.anaconda.com/download#downloads) but we recommend miniconda)

#### Setup

- Create a conda environment with the required packages:

  ```bash
  conda env create -f <path-to-workshop-odsc-folder>/environment.yaml
  ```

- Activate the environment:
  ```bash
  conda activate workshop-odscwest-missingdata
  ```

#### Cleanup

- Deactivate the environment:
  ```bash
  conda deactivate
  ```
- Remove the environment:
  ```bash
  conda env remove -n workshop-odsc
  ```

### Conda Docker Environment

#### Prerequisites

- [Docker](https://docs.docker.com/get-docker)

#### Run

- Run the docker container:
  ```bash
  docker run -it --rm ydata/workshop-odsc:latest
  ```
