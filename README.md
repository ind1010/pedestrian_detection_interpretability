COS 429 Final Project: Interpretability in Pedestrian Detection

Included in this repository:
* detectron2 zip file - Contains custom [Detectron2](https://github.com/facebookresearch/detectron2) module and custom [pycocotools](https://github.com/cocodataset/cocoapi/tree/master/PythonAPI/pycocotools) module adapted for this project.
* detectron2_fasterrcnn.ipynb - Jupyter notebook for using Detectron2 Faster R-CNN with a subset of the [Caltech Pedestrian Dataset](https://drive.google.com/drive/folders/1IBlcJP8YsCaT81LwQ2YwQJac8bf1q8xF)
* caltech_subset - Contains json annotations files in the COCO format of the training, validation, and test sets used for this project.
* Poster presented at the COS 429 Poster Session on 12/13/2021

Note: The Caltech Pedestrian Dataset is formatted as a series of .vbb files. To use them with Detectron2, we first converted the dataset into the PASCAL VOC format using [this repository](https://github.com/CasiaFan/Dataset_to_VOC_converter) and then converted the resulting dataset to the COCO format using [this repository](https://github.com/yukkyo/voc2coco).
