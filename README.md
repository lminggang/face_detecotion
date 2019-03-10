# face_detecotion

#### 介绍
使用视频捕捉设备实现人脸识别，并在标记出识别任务的姓名

#### 软件架构
使用cv进行视频捕捉，图像处理，图像识别。
sklearn进行标记


#### 安装教程

1. python3: 代码是基于python3来编写的，这个自己找下资料吧很简单。
2. numpy: pip install numpy
3. cv2: pip install opencv-python && pip install opencv-contrib-python
4. sklearn: pip install scikit-learn

#### 使用说明

1. 需要运行get_img.py脚本，会让你输入你的名字，输入后会打开摄像头，后续按q键进行拍照多拍几张用来训练模型使用。
2. 运行face_detection.py文件就开始识别了
3. 大部分代码都有注释，不懂得欢迎 issuse

