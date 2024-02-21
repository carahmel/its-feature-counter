## Set up

In the ITSFeatureCounter directory:

1. Create virtual environment, _featureCounter-env_:
```
python -m venv featureCounter-env
```

2. Activate virtual environment, _featureCounter-env_:
```
source featureCounter-env/bin/activate      (Linux/MacOS)
featureCounter-env\Scripts\activate.bat     (Windows cmd.exe)
featureCounter-env\Scripts\Activate.ps1     (Windows PowerShell)
```

3. Install required packages using  _requirements.txt_:
```
pip install -r resources/requirements.txt
```

## Usage

Within the _featureCounter-env_ environment, the script can be launched by executing
```
python ITSFeatureCounter.py -b <url-to-json>
```
where <url-to-json> is typically https://data.geo.admin.ch/ch.bfe.ladestellen-elektromobilitaet/data/ch.bfe.ladestellen-elektromobilitaet_fr.json

Results will be written to *bornes_recharge_LS.txt* in the ITSFeatureCounter directory. 

Example output:
```
{'Available': 40, 'Occupied': 3, 'OutOfService': 0, 'Unknown': 1, 'TOTAL': 44, 'generatedOn': 'Tue Feb 20 17:41:17 2024'}
```

