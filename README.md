# AC/DC

### 1.灵感

本项目框架与灵感来源于BiliBili工科男孙老师的[这个电路可以把你的柠檬升压到5V](https://www.bilibili.com/video/BV14i4y1o79k?spm_id_from=333.1007.top_right_bar_window_custom_collection.content.click&vd_source=f099999d21b0feab495666ac2b7dfbf7)

因为没有找到该项目类似的开源，就复刻了一个，并会在此基础上进行升级。

### 2.选材

本项目采用MPS设计的MP3416电源管理芯片，此芯片静态电流超低，支持0.86—5.5V的输入，1.8—5.5V的输出，可以满足干电池（1.5V）转5V的需求。

### 3.电路设计

在MPS的官网给出了示例电路，1.1版本根据示例电路设计，未加改动。

![MP3416](https://media.monolithicpower.cn/catalog/product/cache/ccb9ba928e4f463ae145b55d0127b66f/M/P/MP3416_217_1.jpg?_gl=1*q7ulr*_ga*NDM5NDA5OTU2LjE2NjAyMjE1NzY.*_ga_CFCF3V5MZM*MTY2MDIyMTkwNy41LjAuMTY2MDIyMTkwNy42MA..&_ga=2.142061431.436018224.1660221578-439409956.1660221576 )



### 4.PCB设计

本项目用立创EDA设计。1.1版本为简单连线设计，在后续会更新为铺铜的走线方式，与MPS官网及孙老师的设计类似。



### 5.外壳设计

本项目外壳为3D打印，通过6颗M2螺丝固定，稳定不晃动，没有任何装饰花纹。



**本项目为小白的第一个项目，视频发布在BiliBili小郝同学的创意坊，欢迎各位大佬指点、完善。**