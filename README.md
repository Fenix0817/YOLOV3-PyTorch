# YOLOV3-PyTorch
This a comprehensive implementation on YOLO V3. It includes training, testing, detecting using local images and using webcam.
Besides this repo, I have a blog post that elaborates the key concepts in YOLO and more details about the coding process. [Click here!](http://leiluoray.com/2018/11/10/Implementing-YOLOV3-Using-PyTorch/)

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
@article{yolo,
  title={You Only Look Once: Unified, Real-Time Object Detection},
  author={Redmon, Joseph and Farhadi, Ali},
  journal = {arXiv},
  year={2016}
}

@article{yolov2,
  title={YOLO9000: Better, Faster, Stronger},
  author={Redmon, Joseph and Farhadi, Ali},
  journal = {arXiv},
  year={2016}
}

@article{yolov3,
  title={YOLOv3: An Incremental Improvement},
  author={Redmon, Joseph and Farhadi, Ali},
  journal = {arXiv},
  year={2018}
}

https://github.com/marvis/pytorch-yolo2
https://github.com/pjreddie/darknet
https://github.com/eriklindernoren/PyTorch-YOLOv3
https://github.com/ayooshkathuria/pytorch-yolo-v3
```
