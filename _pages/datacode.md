---
permalink: /datacode/
title: "Data&Code"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Dataset_Mars-Seg

In the Mars exploration mission, it is necessary to construct a series of datasets in the Mars scene for the training and validation of relevant perception algorithms. In 2021, around the semantic segmentation task, NASA's Mars Science Laboratory released the first large-scale Martian terrain dataset called AI4Mars, which includes four types of terrain. However, due to the lack of definition of terrain categories and low annotation accuracy, the dataset does not have practical application value. For this purpose, our team has released a series of datasets named Mars-Seg for semantic segmentation tasks.

The Mars-Seg dataset contains rich high-resolution images of Martian scenes, which helps researchers understand the true Martian landscape. All single channel grayscale images in this dataset are from the Planetary Data System (PDS), covering 1064 high-definition images captured by the Navigation Camera (NAVCAM) and Panoramic Camera (PANCAM) of the Opportunity and Courage Mars rovers (MER); All RGB images were collected from Mars 32k, all from the MastCam camera of the Curiosity Rover (MSL), with a total of 4148 images. Among them, the spatial resolution of the grayscale image in MER Seg is 1024 x 1024, while the color image in MSL Seg is downsampled to 560 x 500 through bilinear interpolation.

In this dataset, by analyzing the difficulties encountered by the detection vehicle during the detection process and the high-risk issues that may be encountered during the task execution, we divide the terrain in the dataset into the following 9 categories:

| Class name                 | Class definition                                                     | legend                                                         |
| ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Martian Soil | Unconsolidated or poorly consolidated weathered materials; Smaller particle size, below 1mm, with relatively lower fluidity; Due to the influence of terrain, ridges will not form and the color tends to be red. | <img src="..\images\pic\exm1.png" alt="image-20220507173101076" style="zoom:50%;" /> |
| <br />Sands      | Granular matter, very small rocks with a diameter of 1 to 2 mm; Rock is formed by weathering and erosion; There are windward slopes and leeward slopes, with a ridge in the middle, which has relatively strong fluidity and is mainly dark in color. | <img src="..\images\pic\image-20220507173119751.png" alt="image-20220507173119751" style="zoom:50%;" /> |
| <br />Gravel     | Smaller than rock particles, but rougher than sand particles, formed by weathering and erosion of rocks, with a grayish color. | <img src="..\images\pic\image-20220507173131095.png" alt="image-20220507173131095" style="zoom:50%;" /> |
| <br />Bedrock    | Complete new mineral rocks beneath the weathering layer on the surface of the continental crust; Flat than stone, with a grayish white color; More covered by soil layers, buried at a depth of one meter.| <img src="..\images\pic\image-20220507173200263.png" alt="image-20220507173200263" style="zoom:50%;" /> |
| <br />Rocks      | A small rock mass that falls off from a large rock mass due to external forces, with a rough surface, hard texture, irregular shape, and more abrupt, with a color that leans towards blue.| <img src="..\images\pic\image-20220507173213432.png" alt="image-20220507173213432" style="zoom:50%;" /> |
| Tracks       | Detecting the trajectory left by the vehicle after entering.                                      | <img src="..\images\pic\image-20220507173226008.png" alt="image-20220507173226008" style="zoom:50%;" /> |
| Shadows          | The shadows projected by detection vehicles, rocks, etc. under illumination.                             | <img src="..\images\pic\image-20220507173246046.png" alt="image-20220507173246046" style="zoom:50%;" /> |
| Background       | Categories such as distant mountains and sky.                                        | <img src="..\images\pic\image-20220507173257502.png" alt="image-20220507173257502" style="zoom:50%;" /> |
| Unknown          | Unknown areas beyond the above categories, such as images of the Mars rover itself.                 | <img src="..\images\pic\image-20220507173311377.png" alt="image-20220507173311377" style="zoom:50%;" /> |



<!-- ### **2.文件组成**及使用方法

#### 2.1文件组成

Mars-Seg

├─MER
│  ├─JPEGImages	原始图像（.jpg）
│  └─SegmentationClassPNG	语义分割标签（.png）
└─MSL
    ├─JPEGImages	原始图像（.jpg）
    └─SegmentationClassPNG	语义分割标签（.png）

​	本数据集按照图像格式以及数据来源划分为了两组，其中MER数据集中均为1024 ×1024的灰度图像，MSL数据集中均为560×500的RGB图像。

#### 2.2使用方法

在有监督方法中，可以使用单独的MER或者MSL数据集完成训练、验证和测试；在无监督方法中，可以使用其中的任意一组作为源域数据集，另一组作为目标域数据集进行域适应训练。

#### 3.2数据类别统计

<img src="..\images\pic\counter.png" alt="image-20220507173246046" style="zoom:50%;" />

我们统计了数据集中包含各个类别的图像数量。 -->



### Citation of papers

If you have used our dataset in your research, please remember to cite our paper.

Jiaojiao Li, Shunyao Zi, Rui Song, Yunsong Li, Yinlin Hu, Qian Du, Cov-DA: A Stepwise Domain Adaptive Segmentation Network with Covariate shift Alleviation for Remote Sensing Imagery, IEEE Transactions on Geoscience and Remote Sensing, 60: 1-15, 2022. doi:10.1109/TGRS.2022.3152587. [[PDF]](https://ieeexplore.ieee.org/document/9716091)[[Code]](https://github.com/KL-Ding/TGRS-Cov_DA)

<!-- #### 论文亮点

​	我们提出了一种基于协变量域偏移的逐步域自适应分割网络。具体来说，为了缓解不同传感器采集数据时产生的协变量域偏移，我们设计了一个色彩空间映射统一模块。另外，使用了一个多统计量联合评估模块来捕捉子场景的不同统计特征，用于筛选目标域中高置信度的数据，并通过二次域适应进一步提高分割性能。

```
@ARTICLE{9716091,
  author={Li, Jiaojiao and Zi, Shunyao and Song, Rui and Li, Yunsong and Hu, Yinlin and Du, Qian},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={A Stepwise Domain Adaptive Segmentation Network With Covariate Shift Alleviation for Remote Sensing Imagery}, 
  year={2022},
  volume={60},
  number={},
  pages={1-15},
  doi={10.1109/TGRS.2022.3152587}}
``` -->

### [Google Drive Download Link](https://drive.google.com/drive/folders/1nOe2kNdI11MCohKwVuNoMcl8T7xoPAsS?usp=sharing)

### Many thanks to the participants who built this dataset:

Bobo Xi, Chaoxiong Wu, Huanqing Zhang, Shunyao Zi, Yinle Ma, Songcheng Du, Kexin Wang, Chenxi Ji, Siyao Fan, Chiyu Chen, Hantao Zhou, Shuangying Wei, Mingze He, Qiaoyang Ren, Jiyao Liu, Fangrui Kang, Shaoze Peng, Chaohui Wang, Aohong Sun, Pengju Tian, Siyuan Xu, Xinhang Li, Haoxuan Wang, Xueyao Zhang, Ziquan Wang, Xinyuan Li, Zejun Ou, Hanwen Li, Hao Wen, Jiachao Liu, Penghao Tian, Yan Diao, Yuzhe Liu, Xuan Chen, Zhiyuan Zhang, and Yihong leng.

<!-- #### 构建数据集成员

博士生：席博博、武超雄

硕士生：刘佳超、张欢庆、訾顺遥、马寅乐、杜松乘、田鹏昊、刁妍、刘玉哲、陈轩

本科生：张致源、冷奕泓 -->


<!-- ## Avaiable code -->

