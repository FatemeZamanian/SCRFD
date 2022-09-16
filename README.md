# SCRFD
## Install requiarements

```pip install -r requirements.txt```

## Download onnx model and put theme on root

https://drive.google.com/file/d/1pboyNMUStfv89JkKBRTQtfl2iRKHHZ0g/view?usp=sharing

## Run inference file

``` python3 tools/scrfd.py --kind webcam/image```

If you want to make an inference with the webcam, you must give the webcam index

``` python3 tools/scrfd.py --kind webcam --webcam 0```

If you want to make an inference with a photo, you must give the path of the image

``` python3 tools/scrfd.py --kind image --path image path ```
