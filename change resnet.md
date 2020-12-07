# 针对源码中resnet.py文件的修改
* 在源码中resnet已经给出，但是其中cfg.TRAIN在config中并不存在，针对该问题，直接简单粗暴解决 参考的config文件链接(https://github.com/endernewton/tf-faster-rcnn)，把调用的全部参数直接写进代码中（正在努力把它写会config里）
* 在build_network函数里对blocks进行了修改，在我执行源代码过程中会报类似下图的错误，解决链接（https://github.com/endernewton/tf-faster-rcnn/issues/96） 

* 开始我只是对res50进行更改，后来也把其他也进行了修改
![GitHub Logo](https://github.com/zhoufqing/in-campus-project-trains/blob/main/images/resnet_blobs1.png)
