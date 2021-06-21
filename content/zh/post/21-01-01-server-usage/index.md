---
title: 实验室服务器使用说明
Summary:  
date: 2021-01-01
authors: [mingye-xie]
tags: []

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?
---

使用服务器时请自觉遵守使用说明！

<!--more-->

### 服务器种类
- .158：Nvidia Tesla P100 SXM2 （四核，16GB）
- .249：Nvidia RTX 3090*4 （单核，24GB）
- 本地：Nvidia RTX 1080 Ti （单核，11GB）

### 载入服务器模块
每次登入服务器时均需要加载
#### 显示当前可用的软件清单
module av
#### 加载常用模块
```
module load anaconda3/2019.10 #亦可在自己路径下独立安装anaconda
module load cuda/11.1
module load cudnn/8.0.5
module load gcc/7.3.0
```

### conda简要使用说明
#### 初始化conda shell
`conda init bash`
#### 创建虚拟环境（以testenv举例）  
`conda create -n testenv`
#### 激活虚拟环境
`conda activate testenv`
#### 安装软件包
`conda install numpy`

`conda install pytorch=0.4.0 # 指定具体版本`
#### 退出当前的虚拟环境
`conda deactivate`
#### 查看所有的虚拟环境
`conda env list`
#### 查看当前虚拟环境安装包
`conda list`
#### 删除虚拟环境及其下面的所有包
`conda remove -n testenv —-all`

### 其他说明
#### 软件最低版本需求
在3090上低于该版本将无法正常运行需要GPU的程序
 - pytorch>=1.7.0
 - tensorflow>=2.4.0
#### 服务器资源的分配
 - 使用`nvidia-smi`或者`gpustat`(需使用pip或conda安装)查看当前服务器GPU使用状态
 - 多数程序运行时会默认占用所有可用的GPU，需要长时间使用GPU时，在运行指令前添加`CUDA_VISIBLE_DEVICES`指定具体运行的GPU，例如`CUDA_VISIBLE_DEVICES=0 python main.py`即指定在0号GPU上运行程序
 - 在服务器资源紧张时，将会根据任务优先级对资源进行协调（例如近期需要投会议或期刊的同学可以优先使用）


