This computer vision model is based on YOLOv5.
It applies transfer learning to add a set of contextual data to the pretrained model and allow it to identify balloons in the air.

The code contained in the inference_balloons notebook was used to test the efficiency of the pretrained model and compare that to the performance of our model after applying transfer learning.

Performance metrics of the model can be found below:<br>
<img src="https://github.com/MukundShankar-dev/aerial-object-classification/blob/main/outputs/performance_metrics/aerial-model-statistics.png" width="500">
<img src="https://github.com/MukundShankar-dev/aerial-object-classification/blob/main/outputs/performance_metrics/aerial-precision-recall.png" width="500">

Before applying transfer learning:<br>
<img src="https://github.com/MukundShankar-dev/aerial-object-classification/blob/main/outputs/pretrained_model/white-balloon-img.jpeg" width="341">
<img src="https://github.com/MukundShankar-dev/aerial-object-classification/blob/main/outputs/pretrained_model/hot-air-balloons-img.jpeg" width="341">

After applying transfer learning:<br>
<img src="https://github.com/MukundShankar-dev/aerial-object-classification/blob/main/outputs/transfer_learned_model/white-balloon-img.jpeg" width="341">
<img src="https://github.com/MukundShankar-dev/aerial-object-classification/blob/main/outputs/transfer_learned_model/hot-air-balloons-img.jpeg" width="341">

More examples can be found in the [outputs folder](https://github.com/MukundShankar-dev/aerial-object-classification/tree/main/outputs) of this repository.

More information can be found in this [Google Drive folder](https://drive.google.com/drive/folders/1KSwvDx5iDrfFhtfekvSG7CQrM52SoK8K?usp=sharing).
To view the videos, please use the "outputs" folder within the drive.
