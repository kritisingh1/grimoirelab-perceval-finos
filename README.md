# perceval-finoss [![Build Status](https://travis-ci.org/Bitergia/grimoirelab-perceval-finoss.svg?branch=master)](https://travis-ci.org/Bitergia/grimoirelab-perceval-finoss) [![Coverage Status](https://img.shields.io/coveralls/Bitergia/grimoirelab-perceval-finoss.svg)](https://coveralls.io/r/Bitergia/grimoirelab-perceval-finoss?branch=master)

Bundle of Perceval backends for FINOSS ecosystem.

## Backends

The backends currently managed by this package support the next repositories:

* FINOSS meetings attendance

## Requirements

* Python >= 3.4
* python3-requests >= 2.7
* grimoirelab-toolkit >= 0.1.9
* perceval >= 0.12

## Installation

To install this package you will need to clone the repository first:

```
$ git clone https://github.com/Bitergia/grimoirelab-perceval-finoss.git
```

Then you can execute the following commands:
```
$ pip3 install -r requirements.txt
$ pip3 install -e .
```

In case you are a developer, you should execute the following commands to install Perceval in your working directory (option `-e`) and the packages of requirements_tests.txt.
```
$ pip3 install -r requirements.txt
$ pip3 install -r requirements_test.txt
$ pip3 install -e .
```

## Examples

### FINOSS meetings attendance

```
$ perceval 

```

## License

Licensed under GNU General Public License (GPL), version 3 or later.
