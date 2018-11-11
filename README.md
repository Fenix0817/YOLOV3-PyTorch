# YOLOV3-PyTorch

## Installation
```
git clone https://github.com/Ray-Luo/YOLOV3-PyTorch.git
cd YOLOV3-PyTorch/
sudo pip3 install -r requirements.txt
wget https://www.dropbox.com/s/bnwucfzv6torx2t/weights.zip
wget https://www.dropbox.com/s/qfnd3p47td991vj/sample.zip
unzip -q weights.zip
unzip -q sample.zip
```

## Train
`python3 ./train.py`

## Detect
`python3 ./detect.py`

## Camera
`python3 ./camera.py`

## Test
`python3 ./test.py`

## Credit
```
@article{yolov3,
  title={YOLOv3: An Incremental Improvement},
  author={Redmon, Joseph and Farhadi, Ali},
  journal = {arXiv},
  year={2018}
}
```
```
https://github.com/marvis/pytorch-yolo2
https://github.com/pjreddie/darknet
https://github.com/eriklindernoren/PyTorch-YOLOv3
https://github.com/ayooshkathuria/pytorch-yolo-v3
```
