---
permalink: /datacode/
title: "Data&Code"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Dataset_ZS-Mars

 10 categories:

| Class name                 | Class definition                                                     | legend                                                         |
| ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Martian Soil | Unconsolidated or poorly consolidated weathered materials on Mars, with a reddish color, will not form ridges due to the influence of terrain, and have relatively low fluidity. | <img src="..\images\pic\class1.png" alt="image-1" style="zoom:50%;" /> |
| <br />Sands      | The particulate matter composed of small rocks on Mars is generally formed by weathering and erosion of rocks, usually forming a ridge of windward and leeward slopes, with relatively strong fluidity. | <img src="..\images\pic\class2.png" alt="image-2" style="zoom:50%;" /> |
| <br />Gravel     | The particulate matter on Mars is generally formed by weathering and erosion of rocks, which are rougher than sand and smaller than rock particles, with average fluidity. | <img src="..\images\pic\class3.png" alt="image-3" style="zoom:50%;" /> |
| <br />Light Toned Veins    | A landform on Mars composed of patches of gravel and rocks, with varying depths of veins/extensional stripes, usually dominated by rocks and covered by gravel.| <img src="..\images\pic\class4.png" alt="image-4" style="zoom:50%;" /> |
| <br />Float Rocks      | Small rocks that have fallen off the surface of Mars from large rocks, appearing in block or oval shape, with a strong and brittle texture, larger than the particles of gravel, and almost no gravel.| <img src="..\images\pic\class5.png" alt="image-5" style="zoom:50%;" /> |
| Igneous Rocks       | A type of rock on Mars formed by magma ejecting from the surface or invading the crust, cooling and solidifying. It has obvious mineral crystal particles or pores, and the color of the rock is black with irregular shapes; Rocks have varying volumes and lack fluidity.                                      | <img src="..\images\pic\class6.png" alt="image-6" style="zoom:50%;" /> |
| Sedimentary Rocks          | A type of rock on Mars that is formed by the consolidation of loose sediment in layers, usually with a certain layered texture; Not containing or containing a small amount of sand; The rock has a large volume and lacks fluidity; Sediment generally refers to loose debris, such as gravel, sand, clay, plaster, etc.                             | <img src="..\images\pic\class7.png" alt="image-7" style="zoom:50%;" /> |
| Tracks       | The pattern left by the wheels of the Mars surface exploration vehicle after passing through soft soil or sand. The close-up image contains obvious wheel patterns, while the close-up image shows a blurry shape of the wheel patterns, showing long traces of heavy objects dragging.                                        | <img src="..\images\pic\class8.png" alt="image-8" style="zoom:50%;" /> |
| Rover Components       | Part of the structure present on a Mars rover.                                        | <img src="..\images\pic\class9.png" alt="image-9" style="zoom:50%;" /> |
| Unknown          | Unknown areas beyond the above categories, such as images of the Mars rover itself.                 | <img src="..\images\pic\class10.png" alt="image-10" style="zoom:50%;" /> |



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

