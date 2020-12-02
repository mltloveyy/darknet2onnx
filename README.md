# darknet2onnx
yolov3, yolov3-tiny, yolov3-spp, yolov4, yolov4-tiny convert to onnx model

Environment:
Windows10
numpy=1.14.3
onnx=1.4.1

Run script：python darknet2onnx.py --model='' --category_num=''
The format of 'model' must be '[yolov3|yolov3-tiny|yolov3-spp|yolov4|yolov4-tiny]-[{dimension}] where dimension could be a single number (e.g. 288, 416, 608) or WxH (e.g. 416x256)
'category_num' means the number of object categories
e.g. python darknet2onnx.py --model=yolov4-tiny-512x1024 --category_num=1
