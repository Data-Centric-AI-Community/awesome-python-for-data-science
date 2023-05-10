# ODSC Workshop: Data-Centric AI tuning - How and why? 

Get started in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ydataai/ydata-synthetic/blob/master/examples/regular/models/CTGAN_Adult_Census_Income_Data.ipynb)

## Data-Centric AI
*"**Data-Centric AI** is the process of building and testing AI systems by focusing on data-centric operations (i.e cleaning, pre-processing, balancing and augmenting) rather than model-centric operations (ie. hyper-parameters selection, architectural changes,etc)"*

### Dataset

The dataset used for this workshop is the IEEE-Fraud Detection can be found in [Kaggle](https://www.kaggle.com/c/ieee-fraud-detection).

This workshop/tutorial covers the following steps:
- Data Profiling
- Data Preparation & iteration
- Synthetic data generation
- Data pipelines with Scikit-learn & the importance of data pipelines

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
  conda activate workshop-odsc
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
