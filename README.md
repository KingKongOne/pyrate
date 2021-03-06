## Pyrate &mdash; the Python AIS Tools Environment

[![Documentation Status](https://readthedocs.org/projects/pyrate-ship/badge/?version=latest)](http://pyrate-ship.readthedocs.io/en/latest/?badge=latest)            
[![Coverage Status](https://coveralls.io/repos/github/willu47/pyrate/badge.svg?branch=test_db)](https://coveralls.io/github/willu47/pyrate?branch=test_db)
[![Build Status](https://travis-ci.org/willu47/pyrate.svg?branch=master)](https://travis-ci.org/willu47/pyrate)
[![Code Issues](https://www.quantifiedcode.com/api/v1/project/47c974bd83ed47ce88dac312464ab3b0/badge.svg)](https://www.quantifiedcode.com/app/project/47c974bd83ed47ce88dac312464ab3b0)

Pyrate is a software architecture and suite of algorithms for the analysis of [AIS] (http://en.wikipedia.org/wiki/Automatic_Identification_System) data originating from ship-borne transceivers and collected by satellites and shore-based receivers. The different tools engage in an efficient and modular way, hence they are substitutable and extendable in a dynamic fashion. The primary goal is to validate and clean the dataset, extract information on shipping patterns and shipping routes. To make information easily discoverable, the data is stored in a variety of database types and formats.

### Features

* Python-based
* Parallel cleaning and writing of data files (.csv, .xml) into postgreSQL
* Building of a vessel ID&ndash;transponder ID history for ship identification
* Injection of artificial messages to ‘navigate’ vessel around land (coming soon)
* Machine-learning module for passage/voyage discovery (coming soon)
* Guide with cheat sheets (under construction)
* Visualisation of shipping activity on map using this organisation’s repository [shipviz](https://github.com/UCL-ShippingGroup/shipviz) (coming soon)

### Usage/requirements

Pyrate requires an installation of Python 3, Postgresql 9.2+  and optionally Neo4j 2.1.7.

### Contributions

We're very happy receive contributions to our repository or integrate suggestions you may have. Please get in touch with us via github, or open an issue or pull request.

### Further information

For further information please visit the [pyrate wiki](https://github.com/UCL-ShippingGroup/pyrate/wiki) which contains full details of the architecture and algorithms, as well as guides for users and developers.
For questions please visit the [issue page](https://github.com/UCL-ShippingGroup/pyrate/issues).
