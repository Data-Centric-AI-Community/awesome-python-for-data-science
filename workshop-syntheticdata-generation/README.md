# Workshop: Synthetic data generation - How and why? 

Get started in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Data-Centric-AI-Community/awesome-python-for-data-science/blob/main/workshop-syntheticdata-generation/)

## Synthetic data
**Synthetic data** is artificially generated information that mimics the statistical properties of real-world data but does
not directly correspond to real events or individuals. This type of data is created through algorithms and statistical models,
such as generative adversarial networks (GANs) or other simulation techniques. The primary purpose of synthetic data is to serve
as a substitute for real data in situations where using actual data could be problematic, such as in scenarios involving privacy concerns,
data scarcity, or sensitive information. By using synthetic data, organizations can conduct testing, training, and research
in a privacy-compliant manner, enabling more extensive and diverse data analysis while mitigating the risk of exposing real data.

### Dataset
The data used is the [Adult Census Income](https://www.kaggle.com/datasets/uciml/adult-census-income) which we will fecth
by importing the pmlb library (a wrapper for the Penn Machine Learning Benchmark data repository).

This workshop/tutorial covers the following steps:
- Data Profiling
- Data Preparation & iteration
- Synthetic data generation
- Synthetic data quality evaluation

## Quickstart

### Conda environment

#### Prerequisites

- [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) (it can either be installed with [miniconda](https://docs.conda.io/en/latest/miniconda.html) or [anaconda](https://www.anaconda.com/download#downloads) but we recommend miniconda)

#### Setup

- Create a conda environment with the required packages:

  ```bash
  conda env create -f <path-to-workshop-folder>/environment.yaml
  ```

- Activate the environment:
  ```bash
  conda activate workshop-syntheticdata
  ```

#### Cleanup

- Deactivate the environment:
  ```bash
  conda deactivate
  ```
- Remove the environment:
  ```bash
  conda env remove -n workshop-syntheticdata
  ```

### Conda Docker Environment

#### Prerequisites

- [Docker](https://docs.docker.com/get-docker)

#### Run

- Run the docker container:
  ```bash
  docker run -it --rm ydata/workshop-syntheticdata:latest
  ```
