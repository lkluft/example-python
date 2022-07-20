# Example repository (Python)

This git repository is a minimal example to show how to structure a Python
package, and how to use GitHub Actions to automatically run tests and build
documentation for your software.

## Install the package


Create a new environment will all dependencies and make it the active environment
```sh
conda env create -f environment.yml
conda activate mypackage
```

Inspect information about the environment and list all installed packages
```sh
conda info
conda list
```

Install our own package in the environment
```sh
python3 -m pip install .
```

## Run tests

Run the test suite
```sh
pytest .
```

## Build documentation

Auto-generate documentation
```sh
cd docs/
make html
```

The generated HTML files are stored in ` docs/build/html`.

When commits are pushed or merged to the remote repository, a new version of
the documentation is build and published on
[GitHub pages](https://lkluft.github.io/example-python).

---

Further information
* [Setuptools - library to facilitate packaging Python projects](https://setuptools.pypa.io)
* [Sphinx - Python documentation generator](https://sphinx-doc.org)
* [pytest - A full-featured Python testing framewor](https://docs.pytest.org)
* [GitHub Actions - automate your software workflows](https://github.com/features/actions)
* [GitHub Pages - Host web sites directly from your repository](https://pages.github.com)
