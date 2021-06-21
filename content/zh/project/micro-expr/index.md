---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "微表情识别"
summary: "Micro-expression recognition"
authors: [jinjie-chen]
tags: []
categories: []
date: 2021-06-21T10:50:00+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
featured: true

image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### 背景介绍
微表情(Micro-expression)是人们在试图隐藏/压抑真实情感时出现的细微的面部表情。
不同于宏表情，微表情变化细微，动作幅度小，难以观察和辨别；而且发生时间短暂，持续时间不超过0.5s；微表情人们在试图隐藏/压抑真实情感时出现，是自发的，无意识的，可以看作是人的真实情感的“泄露”。


### 应用场景
因此，微表情识别(MER)研究使人们对微妙的面部动作有了更强的意识和敏感性，是理解人类情绪和情感表达的重要课题，已被心理学、社会学、神经科学、计算机视觉等多个学科所探索。广泛应用于警察询问、临床诊断、抑郁症分析、商务谈判等领域

### 已有成果
- 使用对抗生成网络生成微表情伪样本，从根本上解决样本多样性问题，在MEGC2019冠军模型上可以提升10%精度；
- 基于2D CNN的backbone，以视频作为输入，能同时学习时空域上的特征，形成端到端的训练，在CASMEII数据集上达到92%的F1；
