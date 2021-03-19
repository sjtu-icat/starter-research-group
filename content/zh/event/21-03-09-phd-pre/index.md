---
title: 博士组会汇报

event: 实验室汇报
# event_url: https://example.org

location: iCAT会议室
# address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: StyleGAN及其变体介绍
abstract: "StyleGAN及其变体介绍"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-03-09T13:00:00Z"
# date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

url_code: ""
url_pdf: ""
url_slides: "slides/GAN.pptx"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["huayu"]
---

生成器：利用随机采样的隐空间编码生成真实度极高的合成图片，例如StyleGAN等

编码器：将真实图片转换为隐空间编码，以便于后续的编辑和生成

预测器：判断生成图片的语义信息，例如人物的性别、是否微笑等

属性编辑：对隐空间编码进行特定向量方向的操控，以达到对图片属性编辑的目的

