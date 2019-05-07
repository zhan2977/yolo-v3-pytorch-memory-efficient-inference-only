# yolo-v3-pytorch-memory-efficient-inference-only

An memory-efficient implementation of YOLO v3 (inference only).

### Install Requirements

numpy

torch>=1.0

torchvision

matplotlib

tensorflow

tensorboard

terminaltables

pillow

tqdm

### Download pretrained weights

download the pretrained weights from this link:
https://www.dropbox.com/s/kdvvl3nqyxl8l3z/xiwen.npz?dl=0
then put it into the weights/ directory

### Inference

Uses pretrained weights to make predictions on images.
$ python3 detect.py --image_folder data/samples/ --img_size 608
