---
permalink: /datacode/
title: "Data&Code"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Dataset_ZSMars

To facilitate the zero-shot classification task focusing on Mars scenes, we reclassified the image categories within the collected public datasets. By reviewing the two versions of the Mars surface image datasets, MSL (v1) and MSL (v2), we identified overlapping categories and inconsistencies in size and color across images. To resolve these issues, we standardized the size and color of the images across the datasets and redefined the image categories specific to the MSC. We then formed an annotation team to conduct visual image annotation on the revised ZSMSC dataset, now named ZSMars.

In this dataset, we established 10 categories:

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


### Citation of papers

If you have used our dataset in your research, please remember to cite our paper.

Xiaomeng Tan, Bobo Xi, Haitao Xu, Jiaojiao Li, Yunsong Li, Changbin Xue, and Jocelyn Chanussot. A Lightweight Framework With Knowledge Distillation for Zero-Shot Mars Scene Classification[J]. IEEE Transactions on Geoscience and Remote Sensing, 2024, 62: 1–16. [[PDF]](https://ieeexplore.ieee.org/document/10699382)[[Code]](https://github.com/XM-Tan/KDMSC)

<!-- #### 

```
@ARTICLE{10699382,
  author={Tan, Xiaomeng and Xi, Bobo and Xu, Haitao and Li, Jiaojiao and Li, Yunsong and Xue, Changbin and Chanussot, Jocelyn},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={A Lightweight Framework With Knowledge Distillation for Zero-Shot Mars Scene Classification}, 
  year={2024},
  volume={62},
  number={},
  pages={1-16},
  keywords={Mars;Visualization;Semantics;Feature extraction;Scene classification;Image recognition;Microwave integrated circuits;Accuracy;Transformers;Data models;Knowledge distillation (KD);lightweight model;Mars scene classification (MSC);zero-shot learning (ZSL)},
  doi={10.1109/TGRS.2024.3470526}}
``` -->

### [Google Drive Download Link](https://drive.google.com/drive/folders/1H0rA5CFzubRzLufm9y0YpSDPYMv63r5k?usp=sharing)

### Many thanks to the participants who built this dataset:

Xiaomeng Tan, Bobo Xi, Hui Cui, Sihan Bai, Yuxuan Wang, Jingran Li, and Yiming Wang for their support of ZSMars dataset annotations. Specifically, they would also like to thank Prof. Yang Liu for his suggestions on the definitions of the image categories.

<!-- #### 构建数据集成员

席博博

博士生：檀晓萌

硕士生：王一鸣

本科生：崔慧、白思涵、王雨轩、李竟冉 -->


<!-- ## Avaiable code -->

