Dataset **Gesture v1.0** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4MzlfR2VzdHVyZSB2MS4wL2dlc3R1cmUtdjEuMC1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICI3V3YzSVBJUDM3bVp0RHNkMUx2K2w1RnJBZGNGeHRlQVEvbWZEazdaN3BZPSJ9)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Gesture v1.0', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/zenggis/gesture-v1).