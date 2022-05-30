# Dian-ModelZoo📦
*记录点团队国网组训练与部署的的所有训练模型权重。*

<center><img src="https://user-images.githubusercontent.com/77330637/170951971-56708248-8a38-4a77-8790-82d330cc5a7c.png" alt="pics" border="0"></center>

<br>
[TOC]


## 使用说明

本文档用来记录说明规范，请在[Models.md](./Models.md)中写下所训练的权重以及说明。

* 暂时分为Fenghuo-Models和ChangFei-Models两个项目。
* 每个项目暂时分为检测、姿态和部署三类
  * 更加细分的类可以每个部分的负责者自行更改。
* **每次上传权重只在[Models.md](./Models.md)中写下训练权重在服务器上的路径即可**
* 每次上传的时候**一定要写下日期以及上传者名称**，以及相应的文件详细说明（比方说这个采用什么模型，效果怎么样或者问题是什么这类的问题就行当然越详细越好QAQ）。



格式示例：

* /home/lry/projects/Video_dect_pose_mixed/Deploy/Pose/origin_files/hrnet/end2end.onnx
  * lry 2022.5.30
  * 关于hrnet的onnx源文件，大小为101MB
  * 检测效果比较好但是模型太大了，转换为param与.bin后推理速度2FPS

## GitHub简单命令总结

```sh
# 上传一般流程
git add .
git commit -m"add some ..."
git push origin main
# 上传前有时候需要拉取远端来保持同步
git pull
```







