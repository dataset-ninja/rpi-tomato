Dataset **RpiTomato** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/6/n/un/xmI7HlhabZl5AGNTUMrl4L898rLlArz1PmzNT28UQIG3h9ZXNdrPNpoWnNFxiRq7f9ZZ4hriB3mw4L2Or7aTNvUCn9QHoBcs9Y9joYA2FwPr1zCJ5uT16F0bKhmc.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='RpiTomato', dst_path='~/dtools/datasets/RpiTomato.tar')
```
The data in original format can be 🔗[downloaded here](https://zenodo.org/record/5596363/files/Dataset-Greenhouse_Tomato_Raspberry.zip?download=1)