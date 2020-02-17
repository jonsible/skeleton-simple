# Cookiecutter Ansible - Simple

[![Build Status](https://travis-ci.com/jonsible/skeleton-simple.svg?branch=master)](https://travis-ci.com/jonsible/skeleton-simple)

Cookiecutter template for a Ansible role with Molecule testing.

## Features

* Travis-CI: Ready for Travis Continuous Integration testing
* Ansible Galaxy: Ready for deployment to Ansible Galaxy
* Cookiecutter: https://github.com/audreyr/cookiecutter

## Quickstart

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)
```
pip install -U cookiecutter
```
Generate a Python package project::
```bash
cookiecutter https://github.com/jonsible/skeleton-simple.git
# or
cookiecutter https://github.com/jonsible/skeleton-simple.git --no-input role_name=role
```

## License

GPL-3.0-or-later