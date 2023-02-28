This computer vision model is based on YOLOv5.
It applies transfer learning to add a set of contextual data to the pretrained model and allow it to identify balloons in the air.

The code contained in the inference_balloons notebook was used to test the efficiency of the pretrained model and compare that to the performance of our model after applying transfer learning.

Performance metrics of the model can be found below:
![all performance](https://drive.google.com/file/d/1h-HzBI0YJKXTjcviGT4P_alakBW-eTvy/view?usp=sharing)
![PR curve](https://drive.google.com/file/d/193HIg7L--DbYZg208Qd80vR5MxCCXLDQ/view?usp=sharing)

Before applying transfer learning:
![white-untrained](https://drive.google.com/file/d/1wbV2szHOxIQeM0JvVs3eYr1EbwwS2tUT/view?usp=sharing)
![hot-air-untrained](https://drive.google.com/file/d/1siP8GUAJv9fTgACYzMOO_5QmhTesN7rh/view?usp=share_link)
https://user-images.githubusercontent.com/70209741/221981608-4f33a291-7430-4b07-9f07-297e66ef321f.mp4

After applying transfer learning:
![white-trained](https://drive.google.com/file/d/1NnhA-EbDFPUjvlUlFcqL9oZB4WMbPfsH/view?usp=share_link)
![hot-air-trained](https://drive.google.com/file/d/1KSYY2Vm8mbyq6v0v87SBpbfbOjv9z1Dv/view?usp=share_link)
https://user-images.githubusercontent.com/70209741/221981813-8c35b36c-ecea-4a58-a19d-06d46a0b16f7.mp4

More examples can be found in the outputs folder of this repository

More information can be found in this [Google Drive folder](https://drive.google.com/drive/folders/1KSwvDx5iDrfFhtfekvSG7CQrM52SoK8K?usp=sharing).
To view the videos, please use the "outputs" folder within the drive.
