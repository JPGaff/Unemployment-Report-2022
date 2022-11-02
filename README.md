# Unemployment-Report-2022

## Setup
May need to do if python not found

conda activate base

Create & activate a virtual enviornment

'''sh
conda create -n unemployment-env python=3.8

conda activate unemployment-env

'''

'''sh
pip install -r requirement.txt
'''
## Configuration

Obtain API Key from Alphavantage

Create local .env and provide key"

'''
ALPHAVANTAGE_API_KEY="____"
'''


## USAGE

run example
'''sh
python app/my_script.py
'''

run unemployment
'''
python app/unemployment.py
'''

Run stocks report:

```sh
python app/stocks.py
```