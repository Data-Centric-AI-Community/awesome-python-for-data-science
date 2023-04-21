# Data Science Workshop

## Conda Local Environment

### Prerequisites

- [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) (it can either be installed with [miniconda](https://docs.conda.io/en/latest/miniconda.html) or [anaconda](https://www.anaconda.com/download#downloads) but we recommend miniconda)

### Setup

- Create a conda environment with the required packages:

  ```bash
  conda env create -f <path-to-workshop-odsc-folder>/environment.yaml
  ```

- Activate the environment:
  ```bash
  conda activate workshop-odsc
  ```

### Cleanup

- Deactivate the environment:
  ```bash
  conda deactivate
  ```
- Remove the environment:
  ```bash
  conda env remove -n workshop-odsc
  ```

## Conda Docker Environment

### Prerequisites

- [Docker](https://docs.docker.com/get-docker)

### Run

- Run the docker container:
  ```bash
  docker run -it --rm ydata/workshop-odsc:latest
  ```
