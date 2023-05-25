# ⚙️ Installation

To use `ydata-profiling`, you can simply install the package from `pip`.

First, create a virtual/conda environment:

```
conda create -n profiling-env python=3.10
conda activate profiling-env
```

And install `ydata-profiling`. In this case, we declare the extra `[notebook]` that adds support for rendering the report in Jupyter notebook widgets.

```
pip install -U "ydata-profiling[notebook]"
```

# ▶️ Quickstart
Once installed, you just need to `import` the module. Then, using `ydata-profilig` is a simple two-step process:

1. Create a `ProfileReport`
2. Use a `to_notebook_iframe()` function to render the report. You can also save the report to an **html** or **json** file.

# 🪐 Notebook
Check the notebook to learn about the main functionalities provided in the package: https://github.com/Data-Centric-AI-Community/awesome-python-for-data-science/blob/main/dask-demo-day/ydata-profiling-dask-demo-day.ipynb


