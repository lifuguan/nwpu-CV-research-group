---
title: Multiple Papers of Our Team Have Been Accepted by CVPR 2022
date: 2022-03-02T03:42:32.972Z
draft: false
featured: false
image:
  filename: cvpr_2022_press_release_1240x700.jpeg
  focal_point: Smart
  preview_only: false
---
CVPR 2022 officially released the list of accepted papers. Multiple papers from our team are included.

<!--more-->

## 基于样例查询机制的在线动作检测

Authors：杨乐,韩军伟,张鼎文

![](https://zdhxy.nwpu.edu.cn/__local/D/79/34/BD46F5798B7C192E79A249A64A1_85D899FD_66FE1.png?e=.png)

时序动作定位任务从漫长的视频中发现有意义的动作片段，并标注起止时间和动作类别，在视频中浓缩有效信息，从而服务于智慧监控、内容分析等视频理解任务。考虑到实际应用中，算法需要在线地处理视频流并及时准确地检测出视频中正在发生的动作，在线动作检测成为了一个新兴的研究方向。考虑到已有方法只考虑固定历史片段的信息且无法建模跨视频关系，本文提出样例查询机制：通过在历史片段中和动作类别级别构建有代表性的样例进行在线动作检测。相比已有方法，我们的方案运行速度更快，并取得更高地检测精度，为该领域日后的研究工作提供了简单有效的基准模型。



## 基于增量跨视图互蒸馏学习机制的CT影像生成

Authors: 方超伟,王良,徐君,袁奕萱,张鼎文,韩军伟![](https://zdhxy.nwpu.edu.cn/__local/4/54/E3/7252B849D1D30B87991A6D78A5A_AF98810D_15896.png?e=.png)![](https://zdhxy.nwpu.edu.cn/__local/5/20/E8/62296AE54FB5157A4AEA32FB315_07B2FA10_349AC.png?e=.png)

高分辨率CT影像可以帮助医生及医疗AI系统进行精确的影像学分析与疾病诊断，然而由于人体结构的特点，轴向视角的CT影像很难获得足够高的片间分辨率。为此，本文构建了一种自监督的轴向视角CT切片生成方法，提出了增量跨视图互蒸馏学习机制，利用矢状面视角影像和冠状面视角影像的高分辨率先验构建其与轴向视角影像的一致性约束；通过联合迭代不同视角的影像插值过程，实现轴向视角影像片间分辨率的增量式提升，改善模型应对具有不同层厚的CT影像的鲁棒性。



## 基于鲁棒区域特征生成的零样本目标检测

Authors: 黄培亮,韩军伟,程德,张鼎文

![](https://zdhxy.nwpu.edu.cn/__local/B/9F/AA/9C46C372F49D2C5D4BEDA0EDB0F_CA18EE01_1D342.jpg?e=.jpg)

零样本目标检旨在提升模型对训练阶段不可见目标类的检测能力。传统的零样本学习模型在该任务环境下难以为未见目标生成具有足够类内多样性的区域特征，亦或是牺牲掉部分未见目标与图像背景的可区分性。在本研究中，我们充分考虑到物体检测任务的独特性，提出利用训练图像所包含的丰富的前背景区域特征来同时保持未见目标特征的类内多样性和类间可区分性，首次实现了同时针对可见目标类和不可见目标类的统一目标检测模型，并提供了首个零样本遥感目标检测的benchmark。