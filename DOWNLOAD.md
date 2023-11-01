Dataset **RpiTomato Dataset** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/7/8/Yq/qUWrWJuSCufWPvRXHErXzZVNcvhHZYz2a1gEdIerhcka9XxsDLdCn5tQTFLNjUa34e5ZsT4LlujTcKBgP9uy11mFVrjZO2h1FLbkzYJ8F61g15yuWeEpz0qibSwR.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='RpiTomato Dataset', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://zenodo.org/record/5596363/files/Dataset-Greenhouse_Tomato_Raspberry.zip?download=1).