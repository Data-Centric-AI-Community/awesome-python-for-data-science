# Data Science Workshop

## How to setup

### Prerequisites

- [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) (it can either be installed with [miniconda](https://docs.conda.io/en/latest/miniconda.html) or [anaconda](https://www.anaconda.com/download#downloads) but we recommend miniconda)

### Setup
- Create a conda environment with the required packages:
    ```bash
    conda env create -f <path-to-workshop-ds-folder>/environment.yaml
    ```

- Activate the environment:
    ```bash
    conda activate workshop-ds
    ```

### Cleanup
- Deactivate the environment:
    ```bash
    conda deactivate
    ```
- Remove the environment:
    ```bash
    conda env remove -n workshop-ds
    ```


