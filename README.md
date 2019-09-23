# 明星人脸生成器
&emsp;&emsp;这是一个用StyleGAN训练出的明星人脸生成器，生成效果如下所示。<br /><br /><br />

# 生成示例

## &emsp;&emsp;单张样本
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/example1.png)<br/><br/>
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/example2.png)<br/><br/>
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/example3.png)<br/><br/>

## 概览（有筛选）
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/64_examples.jpg)
<br /><br /><br />
查看更多的生成样本可以前往[这里](https://pan.baidu.com/s/1g5ASVZcRoYvClxqsQpShXQ)（提取码：XVAL），是一个含有1万张生成样本的明星脸数据集。<br /><br /><br />

# 明星脸属性编辑
&emsp;&emsp;人脸属性编辑目前支持在笑容、年龄、角度、性别和光照5个维度上对生成人物作出调整。
## 笑容调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/edit_smile.jpg)
<br/><br/>
## 年龄调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/edit_age.jpg)
<br/><br/>
## 角度调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/edit_angle.jpg)
<br/><br/>
## 性别调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/edit_gender.jpg)
<br/><br/>
## 光照调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/edit_exposure.jpg)
<br/><br/><br />

## 想玩更多？
&emsp;&emsp;对于想玩现实明星生成的人，可以考虑使用现实明星编码器（需另外单独购买）,<b>不过潜在法律后果由使用者承担，本人概不负责。</b>下面展示一个由明星脸生成器生成的“迪丽热巴”(只是一个长得像迪丽热巴的“生成人”)。<br/>
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/dlrb/fake-dlrb.png)
## 笑容调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/dlrb/dlrb_smile.jpg)
<br/><br/>
## 年龄调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/dlrb/dlrb_age.jpg)
<br/><br/>
## 角度调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/dlrb/dlrb_angle.jpg)
<br/><br/>
## 性别调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/dlrb/dlrb_gender.jpg)
<br/><br/>
## 发量调整
![Image text](https://github.com/a312863063/seeprettyface-generator-star/blob/master/examples/dlrb/dlrb_hair.jpg)
<br/><br/><br />

# 运行代码
## 环境配置
&emsp;&emsp;Both Linux and Windows are supported, but we strongly recommend Linux for performance and compatibility reasons.<br/>
&emsp;&emsp;64-bit Python 3.6 installation. We recommend Anaconda3 with numpy 1.14.3 or newer.<br/>
&emsp;&emsp;TensorFlow 1.10.0 or newer with GPU support.<br/>
&emsp;&emsp;NVIDIA driver 391.35 or newer, CUDA toolkit 9.0 or newer, cuDNN 7.3.1 or newer.<br/>

## 运行步骤
&emsp;&emsp;1.在model文件夹中按照txt地址下载模型，放在该位置<br/>
&emsp;&emsp;&emsp;&emsp;注明：此模型训练不易，对于开发者来说可能需要付费购买。共有3个模型可以获得，分别是明星脸生成器（前50名购买者免费赠送人脸属性编辑器）、明星脸属性编辑器和现实明星编码器。模型获取方式：见model文件夹下txt文件。<br/>
&emsp;&emsp;2.运行generate_star.py<br/>
<br /><br /><br />
## 获取训练集：[点此下载](http://www.seeprettyface.com/mydataset_page2.html)
![Image text](https://github.com/a312863063/seeprettyface/blob/master/EP001-01.png)
