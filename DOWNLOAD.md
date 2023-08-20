Dataset **RpiTomato** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/w/z/1R/7VL3HK1e7NqzpAkddBZn7au4GyRlIJhPJH64suRKnIwllBtlglIjwu85dYK92hjLlg0xAlrmPgyKvPM3N5bnOC4I5KLcK039wbZYqkuzUImUcRjgXhrV1vNcJeFG.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='RpiTomato', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://zenodo.org/record/5596363/files/Dataset-Greenhouse_Tomato_Raspberry.zip?download=1).