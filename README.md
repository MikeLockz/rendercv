# RenderCV

[![test](https://github.com/sinaatalay/rendercv/actions/workflows/test.yaml/badge.svg?branch=main)](https://github.com/sinaatalay/rendercv/actions/workflows/test.yaml)
[![coverage](https://coverage-badge.samuelcolvin.workers.dev/sinaatalay/rendercv.svg)](https://coverage-badge.samuelcolvin.workers.dev/redirect/sinaatalay/rendercv)
[![pypi-version](https://img.shields.io/pypi/v/rendercv?label=PyPI%20version&color=rgb(0%2C79%2C144))](https://pypi.python.org/pypi/rendercv)
[![pypi-downloads](https://img.shields.io/pepy/dt/rendercv?label=PyPI%20downloads&color=rgb(0%2C%2079%2C%20144))](https://pypistats.org/packages/rendercv)


## Quick Start Guide

> RenderCV doesn't require a $\LaTeX$ installation; it comes with it!

1.  Install [Python](https://www.python.org/downloads/) (3.10 or newer).
2.  Run the command below to install RenderCV.
    ```bash
    pip install rendercv
    ```
3.  Run the command below to generate a starting input file (`Full_Name_CV.yaml`).
    ```bash
    rendercv new "Full Name"
    ```
4.  Edit the contents of `Full_Name_CV.yaml` in your favorite editor (*tip: use an editor that supports JSON Schemas*).
5.  Run the command below to generate your $\LaTeX$ CV.
    ```bash
    rendercv render Full_Name_CV.yaml
    ```

You can find a comprehensive user guide that covers the data model (YAML structure) and adding custom themes in greater detail [here](https://sinaatalay.github.io/rendercv/user_guide).

## Documentation

The source code of RenderCV is well-commented and documented. Reading the source code might be fun as the software structure is explained with docstrings and comments.

A detailed user guide can be found [here](https://sinaatalay.github.io/rendercv/user_guide).

Reference to the code can be found [here](https://sinaatalay.github.io/rendercv/reference).

The changelog can be found [here](https://sinaatalay.github.io/rendercv/changelog).

## Contributing

All contributions to RenderCV are welcome! For development, you will need to clone the repository recursively, as TinyTeX is being used as a submodule:

```bash
git clone --recursive https://github.com/sinaatalay/rendercv.git
```

All code and development tool specifications are in `pyproject.toml`.