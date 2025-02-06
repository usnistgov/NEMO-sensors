# NEMO Sensors

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/NEMO-sensors?label=python)](https://www.python.org/downloads/release/python-3110/)
[![PyPI](https://img.shields.io/pypi/v/nemo-sensors?label=pypi%20version)](https://pypi.org/project/NEMO-sensors/)
[![Changelog](https://img.shields.io/github/v/release/usnistgov/NEMO-sensors?include_prereleases&label=changelog)](https://github.com/usnistgov/NEMO-sensors/releases)

Plugin for NEMO allowing to connect to sensors to collect data and set alerts.

## Installation

```bash
python -m install nemo-sensors
```

in `settings.py` add to `INSTALLED_APPS`:

```python
INSTALLED_APPS = [
    '...',
    'NEMO_sensors',
    # 'NEMO.apps.sensors' Remove old dependency
    '...'
]
```

## Usage

Usage instructions go here.

# Tests

To run the tests:
```bash
python runtests.py
```
