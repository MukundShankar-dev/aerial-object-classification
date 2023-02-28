This computer vision model is based on YOLOv5.
It applies transfer learning to add a set of contextual data to the pretrained model and allow it to identify balloons in the air.

The code contained in the inference_balloons notebook was used to test the efficiency of the pretrained model and compare that to the performance of our model after applying transfer learning.

Performance metrics of the model can be found below:
![all performance](https://drive.google.com/file/d/1h-HzBI0YJKXTjcviGT4P_alakBW-eTvy/view?usp=sharing)
![PR curve](https://drive.google.com/file/d/193HIg7L--DbYZg208Qd80vR5MxCCXLDQ/view?usp=sharing)

Before applying transfer learning:
![white-untrained](https://github.com/MukundShankar-dev/aerial-object-classification/blob/main/outputs/pretrained_model/white-balloon-img.jpeg)
![hot-air-untrained](https://github.com/MukundShankar-dev/aerial-object-classification/blob/main/outputs/pretrained_model/hot-air-balloons-img.jpeg)
![white-untrained-vid](https://github.com/MukundShankar-dev/aerial-object-classification/blob/main/outputs/pretrained_model/white-balloon-vid.mp4)

After applying transfer learning:
![white-trained](https://drive.google.com/file/d/1NnhA-EbDFPUjvlUlFcqL9oZB4WMbPfsH/view?usp=share_link)
![hot-air-trained](https://drive.google.com/file/d/1KSYY2Vm8mbyq6v0v87SBpbfbOjv9z1Dv/view?usp=share_link)

More examples can be found in the [outputs folder](https://github.com/MukundShankar-dev/aerial-object-classification/tree/main/outputs) of this repository.

More information can be found in this [Google Drive folder](https://drive.google.com/drive/folders/1KSwvDx5iDrfFhtfekvSG7CQrM52SoK8K?usp=sharing).
To view the videos, please use the "outputs" folder within the drive.
