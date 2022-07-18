# Example repository (Python)

This git repository is a minimal example to show how to structure python code
and run automated tests and documentation using Github CI.

## Install the package


Install the package and its dependencies
```sh
python -m pip install -r requirements.txt
python -m pip install .
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

The will generate HTML files in
```
docs/build/html
```

---

Further information
* [Sphinx - Python documentation generator](https://sphinx-doc.org)
* [pytest - A full-featured Python testing framewor](https://docs.pytest.org)
