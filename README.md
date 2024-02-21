## ITS feature counter

This Binder repository allows the ITSFeatureCounter script to be executed directly from a browser.


## Usage

Run https://mybinder.org/v2/gh/carahmel/its-feature-counter/HEAD?labpath=ITS-feature-counter.ipynb in your browser and wait for the Binder to finish building the image.

Once the image is built, JupyterLab will open with the ITS-feature-counter notebook ready to be run.

This notebook is fully editable within the browser. As such, the path to ich-tanke-strom.ch's JSON file can be updated if necessary.

Results will be written to *results.txt* in the main directory. Multiple runs of the script will append new results to *results.txt*.


Example output:
```
{'Available': 40, 'Occupied': 3, 'OutOfService': 0, 'Unknown': 1, 'TOTAL': 44, 'generatedOn': 'Tue Feb 20 17:41:17 2024'}
```

