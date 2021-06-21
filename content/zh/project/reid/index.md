---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "行人重识别"
summary: "Person re-identification"
authors: [suncheng-xiang,hao-chen,mengyuan-guan]
tags: []
categories: []
date: 2021-06-21T10:30:00+08:00

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
行人重识别（Person re-identification, Re-ID)，也称为行人再识别或跨镜追踪；主要实现从一个摄像头捕获的目标行人，到其他不同摄像头检索是否存在相同行人，即进行跨摄像头检索。

### 应用场景
行人重识别技术可以弥补目前固定摄像头的视觉局限, 并可与行人检测、行人跟踪技术相结合, 应用于视频监控、智能安防等领域。

### 已有成果
行人重识别领域由于安全隐私、数据可获取性、标注难度等因素的限制，高质量大规模的真实标注数据依然非常稀缺。针对这类问题，我们针对具体任务场景，利用GTA-5自动构建了多属性有标注数据集。
{{< figure src="./gpr.png" caption="来自标注数据集的行人样本" >}}

### 已发表论文
[1] Xiang S, Fu Y, You G, et al. Unsupervised domain adaptation through synthesis for person re-identification[C]//2020 IEEE International Conference on Multimedia and Expo (ICME). IEEE, 2020: 1-6. [Link](../publication/xiang-2020-unsupervised/)

[2] Xiang S, Fu Y, You G, et al. Taking A Closer Look at Synthesis: Fine-Grained Attribute Analysis for Person Re-Identification[C]//ICASSP 2021-2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2021: 3765-3769. [Link](../publication/xiang-2021-taking/)