# HySDS
Core component for the Hybrid Science Data System


## Prerequisites

- pip 9.0.1+
- setuptools 36.0.1+
- virtualenv 1.10.1+
- prov-es 0.1.1+


## Installation

1. Create virtual environment and activate:
  ```
  virtualenv env
  source env/bin/activate
  ```

2. Update pip and setuptools:
  ```
  pip install -U pip
  pip install -U setuptools
  ```

3. Install prov-es:
  ```
  git clone https://github.com/pymonger/prov_es.git
  cd prov_es
  pip install .
  cd ..
  ```

4. Install hysds:
  ```
  git clone https://github.jpl.nasa.gov/hysds-org/hysds.git
  cd hysds
  pip install .
  ```
