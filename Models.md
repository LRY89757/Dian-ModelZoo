# Models🎈

[TOC]

## 烽火🔥

---

### 检测

* YOLOX-Nano
  * /home/zwr/fenghuo_env/YOLOX/YOLOX_outputs/yolox_nano_reorganized_2/best_ckpt.pth
  * zwr 2022.5.31
  * + 使用该权重时要对输入图片做归一化处理，参考值：
  
      mean = [0.469, 0.481, 0.497]

      std = [0.3, 0.307, 0.314]
    
      该参考值由全部train和val数据集里的120张图片计算得到，通道顺序依次为BGR。
    + 验证集AP：31.33
    + 权重大小：7.25 MB
  

* ...

### 姿态



* a...
  * path
  * usr time
  * description

* ...



### 部署



* YoloX-tiny的ncnn权重
  * `C:\Users\Lenovo\Desktop\fenghuo _demo\ModelZoo\yolox_tiny.bin`
  * `C:\Users\Lenovo\Desktop\fenghuo _demo\ModelZoo\yolox_tiny.param`
  * lry 2022.5.30
  * 模型大小为9MB, 速度大概在7-8FPS左右，还算不错，目前量化成int8还有问题，暂时还是使用的yolox-nano

* ...



## 长飞🛫

### 检测



* YOLOX-Nano

  + /home/zwr/fenghuo_env/YOLOX/YOLOX_outputs/yolox_nano_changfei/best_ckpt.pth
  + zwr 2022.6.1
  + + 使用该权重时要对输入图片做归一化处理，参考值：

      mean = [0.489, 0.5, 0.508]

      std = [0.236, 0.252, 0.275]

      该参考值由全部train和val数据集里的178张图片计算得到，通道顺序依次为BGR。

    + 验证集AP：76.22 (效果不错，推理时建议选用较高阈值)

    + 权重大小：7.24 MB

* ...

### 姿态



* a...
  * path
  * usr time
  * description

* ...



### 部署

* a...
  * path
  * usr time
  * description

* ...

