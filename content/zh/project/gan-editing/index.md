---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "基于GAN的图片属性编辑"
summary: "GAN-based image attribute editing"
authors: [mingye-xie,feng-wang]
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
生成对抗网络（Generative Adversarial Networks， GAN）由两个基础神经网络即生成器（Generator）和判别器（Discriminator）所组成，其中一个用于生成内容，另一个则用于判别生成的内容。GAN能够学习数据集内的特征，进而生成逼近真实数据的高质量的图片。

GAN在图像合成领域的应用已经十分广泛。近期的一些研究表明，在学习合成图像时，GAN 会自发地在隐空间（latent space）中表示出多种可解释属性，如用于人脸合成的性别特征、用于场景合成的光照条件。通过正确识别这些语义，我们可以将 GAN 学习到的知识重新利用，合理地控制图像生成过程，从而实现图像编辑功能的更广泛应用，如人脸操纵和场景编辑。

解释 GAN 潜在空间的关键点在于找到与人类可理解属性相对应的子空间。通过这种方法，将潜码（latent code）向特定子空间的方向移动，即可对应地改变合成图像的语义。

### 应用场景
人脸图像内含有很多的语义属性，例如表情、头发颜色、年龄等，利用GAN可以实现图像的属性编辑，比如改变表情、改变头发颜色。人脸属性编辑可应用在娱乐场景中，比如短视频中的特效，可实现年龄转换、表情变换等功能，也可用于辅助诸如人脸识别，表情识别等其他任务。

### 已有成果
- 设计了一个针对人脸表情编辑的框架，该方案使得编辑后生成的图片质量更高、更真实。
{{< figure src="./face.png" caption="人脸表情编辑效果" >}}

- 利用GTA V自动构建了带标注的室外场景数据集。
{{< figure src="./gos.png" caption="GTA V室外场景数据集" >}}

