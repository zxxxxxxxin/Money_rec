# 人民币识别
TinyMind人民币面值&amp;冠字号编码识别挑战赛
'主要源于 https://github.com/Flyfoxs/ty_m'
'比赛数据地址：https://www.tinymind.cn/competitions/47#property_62'
## 必要安装:
requirement..txt
pip uninstall keras-preprocessing
pip install git+https://github.com/keras-team/keras-preprocessing.git
## 特性:
使用了一个三层的网络，10个epoch后可以达到94%的精度
能在gtx 1050下跑的动
