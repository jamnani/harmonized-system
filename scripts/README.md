# Building dataset

Requirements:

- Python3

To build the dataset, download the JSON file from the UN Comtrade data extraction API. Then execute the conversion script as follows.

```bash
`scripts/convert.py -i <datapackage.json> -o <hscodes.csv>`

# for example:
# scripts/convert.py -i classificationH6.json -o hs2022.csv
```
