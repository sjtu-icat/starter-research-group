---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "文档智能技术"
summary: "Document Intelligence"
authors: [wei-ran,jingsheng-gao]
tags: []
categories: []
date: 2021-06-21T10:55:00+08:00

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
文档智能（Document Intelligence）主要是指对于网页、数字文档或扫描文档所包含的文本、表格以及丰富的排版格式，以及APP界面所包含的布局、内容等信息，通过人工智能技术进行理解、分类、提取以及信息归纳的过程。

### 应用场景
随着数字化进程的加快，文档、图像等载体的结构化分析和内容提取成为关乎企业数字化转型成败的关键一环，自动、精准、快速的信息处理对于生产力的提升至关重要。以商业文档为例，不仅包含了公司内外部事务的处理细节和知识沉淀，还有大量行业相关的实体和数字信息。人工提取这些信息既耗时费力且精度低，而且可复用性也不高，因此，文档智能技术应运而生。

### 已有成果
目前本课题已经具有用于训练的完备数据集， 进行软件测试的大体框架已经构建完成，输入给定的被测软件的.apk文件能够自动执行类似于人的动作（这些动作包括：点击、滑动、文本键入等），并输出相应的UI跳转图。

{{< figure src="./method.png" caption="UI跳转示意图" >}}