# lemon-work-daily-record
record daily work in Lemon

使用facekit工程调试美妆特效，facekit使用新引擎，需要将原始的params.txt配置文件转换为meta.json文件，转换程序为ParamToMetaForMac【使用方法:./ParamToMetaForMac params.txt】。
路径:~/work_rcl
测试特效时，将特效文件夹放到facekit工程的effect文件夹下，并且修改ViewController.m。


2016.11.03
1.形变需求：新增dogcry形变，在dogdog形变的基础上做如下修改：1>.使用zhuzhu形变的嘴边，但是程度较轻；2>.下巴往上收；3>.眼睛再放大一些。
2.如果需要嘴边闭合，需要添加几个三角形：
  96,97,103,
  97,98,102,
  97,102,103,
  98,99,102,
  99,101,102,
  99,100,101
3.配合和设计师调节美妆效果。

2016.11.17
1.triangleTransform()三角变形时，需要注意三角形顶点顺序，程序中BC有除0的风险，会出现黑色。
2.使用nvwang美妆做口红算法测试。

2016.11.22
1.donutalk美颜滤镜url更新为http://astickersos.faceu.mobi/donutalk/beaufilter/assets/ ，与faceu地址有区别。 

2017.01.03
1.faceU 美型的配置与常用形变的配置有所不同，见“faceU美型”文件夹，用tuer形变更新。
