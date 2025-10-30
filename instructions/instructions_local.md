# How to run the tutorial locally

## Goals of the tutorial
This tutorial aims to introduce you to working with images in Python and performing 3D force inference with foambryo. You will learn:

- how to view and interact with images using [napari](https://napari.org/).
- how to perform basic mesh processing
- how to infer cellular forces in 3D images using [foambryo](https://github.com/VirtualEmbryo/foambryo).

## Pre-requisites
You need a working installation of Python on your computer along with either [`uv`](https://docs.astral.sh/uv/) or [`conda`/`mamba`](https://github.com/conda-forge/miniforge). If you aren't sure which to choose, we recommend `mamba`. You can download `mamba` [here](https://conda-forge.org/download/).

## Installation
Follow the installation instructions below. Choose the section based on which system you are using to manage Python.

### uv
To run with [`uv`](https://docs.astral.sh/uv/), do the following in your terminal:

```bash
# clone the repo
git clone https://github.com/kevinyamauchi/embo-bia-2025.git

# navigate into the repo
cd embo-bia-2025

# launch jupyter with uv
uv run --with jupyter jupyter lab
```

This will launch the Jupyter Lab instance in the `embo-bia-2025` directory. Navigate to the `/tutorial` sub-directory to access the tutorial notebooks.

### mamba
To setup your environment with [`mamba`](https://github.com/conda-forge/miniforge)/conda, do the following (replace mamba with conda if you are using conda)

```bash
# clone the repo
git clone https://github.com/kevinyamauchi/embo-bia-2025.git

# navigate into the repo
cd embo-bia-2025

# create the environment
mamba create -f conda_env.yaml

# activate the environment
mamba activate force-inference

# launch jupyter lab
jupyter lab
```

This will launch the Jupyter Lab instance in the `embo-bia-2025` directory. Navigate to the `/tutorial` sub-directory to access the tutorial notebooks.

## Doing the tutorial
We have provided jupyter notebooks in the `/tutorial` directory. Do each notebook starting with `part_0_viewer_intro.ipynb`. There are solutions to each notebook in the /solutions directory. The "bonus excercises" are optional.
