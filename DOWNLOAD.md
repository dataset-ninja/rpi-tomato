Dataset **RpiTomato** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/o/f/Sk/WdpB20P1urM7KnqGdIyLKg5Rhqv8Bc4ujdzwq0lTVVT7JwIxVyvKnyhOWmQ4okalOsq2O8UDnGdNPqms2ftM9C4q1yVzyGWbigS2ysMKTnB0X3hEUsw1tQ9T1ReQ.tar)

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