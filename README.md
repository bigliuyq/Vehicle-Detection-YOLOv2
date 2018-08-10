# Vehicle-Detection-YOLOv2
使用YOLOv2来实现车辆识别

使用YAD2K：https://github.com/allanzelener/YAD2K 把weights文件转化为keras的h5文件

下载相应的YOLO weights和cfg文件:

weight：https://pjreddie.com/darknet/yolov2/ 文件下载;

获得YAD2K;

运行yad2k.py文件，参数依次为：cfg文件路径，weights文件路径，model文件输出路径.

这里使用yolov2-tiny模型的voc版本，运行如下命令：
```
python ./yad2k.py ./yolov2-tiny-voc.cfg ./yolov2-tiny-voc.weights ./model/yolov2-tiny-voc.h5
```
