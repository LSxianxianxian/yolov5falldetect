# yolov5falldetect

在data文件夹下面创建下面四个文件夹：Annotations、images、ImageSets、labels

先运行makeTex.py
再运行voc_label.py

在data文件夹中找到coco.yaml,复制coco.yaml文件在同目录下黏贴换一个名为fall.yaml文件

修改fall.yaml文件内容，包括类别数和类别名

找到models文件夹下的yolov5l.yaml文件，修改yolov5l.yaml中的类别数

找到train.py文件，在train.py文件中三个路径
