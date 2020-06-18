# Yolo-V5  https://github.com/ultralytics/yolov5
conda create --name yolov5 python=3.7 <br>
conda activate yolov5 <br>
conda install pytorch torchvision cudatoolkit=10.2 -c pytorch <br>
conda update -yn base -c defaults conda  <br>
conda install -yc anaconda numpy opencv matplotlib tqdm pillow ipython scipy <br>
conda install -yc conda-forge scikit-image pycocotools tensorboard <br>
conda install -yc spyder-ide spyder-line-profiler <br>
conda install -yc pytorch pytorch torchvision <br>
conda install -yc conda-forge protobuf numpy && pip install onnx==1.6.0 <br>

## Clone repository
(yolov5) $ git clone https://github.com/ultralytics/yolov5.git

## Test installation
(yolov5) $ python detect.py --source ./inference/images/ --weights yolov5s.pt --conf 0.4

## Download weight file for Windows only
from https://drive.google.com/drive/folders/1Drs_Aiu7xx6S-ix95f9kNsA6ueKRpN2J to /weights folder <br>

## Test installation Windows only 
(yolov5) d:\ python detect.py --source ./inference/images/ --weights ./weights/yolov5s.pt --conf 0.4 <br>


