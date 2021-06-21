---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "基于骨架的人类动作识别"
summary: "Skeleton-based human action recognition"
authors: [zefang-yu,yangcheng-li]
tags: []
categories: []
date: 2021-06-21T10:00:00+08:00

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
近年来，基于骨架的动作识别由于其对动态环境和复杂背景的鲁棒性而备受关注，其主要任务为根据输入的一段骨架序列，输出当前对应的动作类别。主流方法通常将关节点数据构建为图（graph）结构，并将图卷积扩展为时空图卷积来提取运动信息。

### 应用场景
基于骨架的动作识别可以服务于人机交互、机器人、VR游戏实时控制等领域。

### 已有成果
构建动作识别数据集时往往需耗费大量的人力物力，缺乏多视角下的动作序列。为解决这一问题，我们基于GTA V游戏构建了大规模360度全视角的虚拟动作数据集GAR-60。
{{< figure src="./gar-60.png" caption="GAR-60数据集部分样本" >}}