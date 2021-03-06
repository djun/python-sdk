# Python-SDK

[![Build Status](https://travis-ci.org/leancloud/python-sdk.svg?branch=master)](https://travis-ci.org/leancloud/python-sdk) [![Python3 Support](https://caniusepython3.com/project/leancloud-sdk.svg)](https://caniusepython3.com/project/leancloud-sdk) [![Codecov](https://img.shields.io/codecov/c/github/leancloud/python-sdk.svg)](https://codecov.io/gh/leancloud/python-sdk)

LeanCloud Python SDK

## Install

```bash
pip install leancloud
```

or

```
easy_install leancloud
```

Maybe you need the `sudo` prefix depends on your OS environment.

## Generate API document

Install dependencies:

```sh
pip install Sphinx
pip install sphinx_rtd_theme
```

```sh
cd apidoc
make html
```

## Run Tests

Configure the following environment variables:

- `APP_ID`
- `APP_KEY`
- `MASTER_KEY`
- `USE_REGION`

Install dependencies:

```sh
pip install -e .'[test]'
```

Run tests:

```sh
nosetests
```

## Linter and Formatter

Currently, flake8 (linter) and black (formatter) are used.
But we are still exploring.

## Release a New Version

1. Edit `changelog` and `setup.py` (`version`).
2. Commit them and send a pull request.
3. The maintainer will review and merge the pull request, then create a new release at GitHub web UI.
4. A new version of the package will be published to PyPI automatically (via GitHub Actions).

## License

License: [GNU LGPL](https://www.gnu.org/licenses/lgpl.html).

Author: asaka (lan@leancloud.rocks)
