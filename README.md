# QGISPlugin-HZAUSoilTexture
使用值范围在0-100间的砂粒和黏粒栅格数据来生成土壤质地图的QGIS插件
该插件需要选取同一区域砂粒和黏粒的值在0-100之间的空间分布栅格图，同时还须用户选择土壤质地分类标准和提供输出文件的路径及名称。
之后用户会得到三个输出文件：
1、栅格图，其中单个像素值是基于用户选择的分类标准所对应的唯一质地值来编码的；
2、矢量图，具有相同质地类型的同质区域表示的矢量地图，属性表包含基于用户所选分类标准的属性名和质地值；
3、文本文件，在质地图的同一输出路径中创建的一个名为“*_TernaryPlot.csv”的文本文件，可供绘制土壤质地三元图时使用。
