# Yolo-V5  https://github.com/ultralytics/yolov5
conda create --name yolov5 python=3.7 <br>
conda activate yolov5 <br>
conda install pytorch torchvision cudatoolkit=10.2 -c pytorch <br>
conda update -yn base -c defaults conda  <br>
conda install -yc anaconda numpy opencv matplotlib tqdm pillow ipython <br>
conda install -yc conda-forge scikit-image pycocotools tensorboard <br>
conda install -yc spyder-ide spyder-line-profiler <br>
conda install -yc pytorch pytorch torchvision <br>
conda install -yc conda-forge protobuf numpy && pip install onnx==1.6.0 <br>
