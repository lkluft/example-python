# Example repository (Python)

This git repository is a minimal example to show how to structure a Python
package, and how to use GitHub Actions to automatically run tests and build
documentation for your software.

## Install the package


Install the package and its dependencies
```sh
python3 -m pip install -r requirements.txt
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

---

Further information
* [Setuptools - library to facilitate packaging Python projects](https://setuptools.pypa.io)
* [Sphinx - Python documentation generator](https://sphinx-doc.org)
* [pytest - A full-featured Python testing framewor](https://docs.pytest.org)
* [GitHub Actions - automate your software workflows](https://github.com/features/actions)
