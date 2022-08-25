# Welcome to the PHDI Geospatial Demo

This repository contains a simple demo of geospatial functionality in the [PHDI (Public Health Data Infrastructure) building blocks](https://github.com/CDCgov/phdi).

## Dependencies
1) Ensure your Python environment (or virtual environment) is on version 3.9.12 or higher.
2) In order to use this demo, you must place valid Smarty credentials in a file called `.credentials/smarty.yaml`.
The text of that file should look like the following:
```yaml
---
  auth_id: [your smarty auth_id]
  auth_token: [your smarty auth_token]
```

## Instructions
Read and run the [Jupyter Notebook](demo-geospatial.ipynb).