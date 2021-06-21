---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "会议摘要"
summary: "Meeting summarization"
authors: [mengnan-qi,hao-liu]
tags: []
categories: []
date: 2021-06-21T10:35:00+08:00

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
会议摘要(meeting summarization),属于多人长对话场景下的文本摘要；就是在会议记录基础上经过加工、整理出来的一种记叙性和介绍性的文件。包括会议的基本情况、主要精神及中心内容。

{{< figure src="./summary.png" caption="摘要内容示例" >}}

### 应用场景
实时自动会议纪要将大大简化繁琐的会议总结工作，可以帮助与会者快速获取会议重要信息，从而做出正确的判断。 

### 已有成果
相比于新闻等结构化的文本，会议文本结构复杂，不同角色的发言相互交错，主题杂糅，语义逻辑破碎，理解其文本语义是对现有深度学习模型的全新挑战。在这项工作中，我们提出了一个具有多任务预训练的分层变压器编解码网络。具体地说，我们在词级编码器上为每个话语屏蔽关键句，并在解码器上生成它们。此外，我们在输入文本中随机屏蔽一些角色对齐，并强制模型恢复原始的角色标签来完成对齐。此外，我们还引入了主题分割机制来约束关注范围，进一步提高了生成摘要的质量。实验结果表明，该模型在满足AMI和ICSI的汇总数据集上优于以往的方法。

