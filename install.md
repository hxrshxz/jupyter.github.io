---
layout: page
title: Installing Jupyter
tagline: Get up and running on your computer
permalink: /install
---

Project Jupyter's tools are available for installation via the [Python Package Index](https://pypi.org/), the leading repository of software created for the Python programming language.

This page uses instructions with [pip](https://pip.pypa.io/en/stable/), [the recommended installation tool for Python](https://packaging.python.org/en/latest/guides/tool-recommendations/#installation-tool-recommendations). If you require _environment management_ as opposed to just installation, look into [conda](https://docs.conda.io/), [mamba](https://mamba.readthedocs.io/), [pipenv](https://pipenv.pypa.io/), and [Homebrew](https://brew.sh).

## JupyterLab

Install JupyterLab with `pip`:

```bash
pip install jupyterlab
```

**Note**: If you install JupyterLab with conda or mamba, we recommend using [the conda-forge channel](https://conda-forge.org/).

Once installed, launch JupyterLab with:

```bash
jupyter lab
```

## Jupyter Notebook

Install the classic Jupyter Notebook with:

```bash
pip install notebook
```

To run the notebook:

```bash
jupyter notebook
```

## Jupyter Desktop

Install Jupyter Desktop with:

```bash
winget install jupyterlab
```

**Note**: you can also install Jupyter Desktop by visiting [JupyterLab Desktop Releases](https://github.com/jupyterlab/jupyterlab-desktop/releases) page.

## Voilà

Install Voilà with:

```bash
pip install voila
```

Once installed, launch Voilà with:

```bash
voila
```

## Homebrew

[Homebrew](https://brew.sh) is a package manager for macOS and Linux.
You can use it to install Jupyter by running:

```bash
brew install jupyterlab
```
