# yolov5_openvino_sdk
an SDK about how to use openvino model transformed from yolov5
## before start
you should read https://github.com/ultralytics/yolov5/issues/891 first to convert yolov5 to openvino.This web is a tutorial that teach u how to transform yolov5(pytorch) to onnx.YOu will get .xml and .bin file after transformation.
## this project(SDK)
1.install [requirements.txt](https://github.com/linhaoqi027/yolov5_openvino_sdk/blob/master/requirements.txt) dependencies.
```bash
pip install -qr requirements.txt
```
This is project is a SDK to use transformed models(.xml and .bin).
