# SCRFD
## Install requiarements

```pip install -r requirements.txt```

## Download onnx model

https://drive.google.com/file/d/1pboyNMUStfv89JkKBRTQtfl2iRKHHZ0g/view?usp=sharing

## Run inferenc file

``` python3 tools/scrfd.py --kind webcam/image```

if you want get webcam inference you may give index of webcame:

``` python3 tools/scrfd.py --kind webcam --webcam 0```

if you want get image inference you may give path of input image:

``` python3 tools/scrfd.py --kind image --path ```
