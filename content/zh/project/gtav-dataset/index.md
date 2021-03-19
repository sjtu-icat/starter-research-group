---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "GTAV虚拟数据集采集"
summary: "ScriptHookV"
authors: [suncheng-xiang, mingye-xie, zefang-yu]
tags: []
categories: []
date: 2021-03-18T22:34:00+08:00

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

url_code: "http://github.com"
url_pdf: "slides/huayu.pdf"
url_slides: "slides/huayu.pptx"
url_video: "http://youtube.com"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

GTA5（侠盗飞车手5，Grand Theft Auto V）是一款开放式游戏。游戏背景的洛圣都市是基于现实中的美国洛杉矶市和加州南部制作的。游戏地图面积252平方公里（不含水域），360平方公里（含水域）。地图里自然景观丰富，包括城市、乡村、高山、森林、沙滩等等。其环境场景的逼真度使得可以利用该游戏生成虚拟数据集。

由于GTA5出色的游戏性，自游戏发售以来，玩家们利用游戏内的功能函数开发了许多脚本，例如自定义车辆的皮肤、人物的衣服，或者生成NPC角色，消除地图上的车辆等。有玩家把这些函数封装成库文件native_db，并开发相关的插件ScriptHookV用于把脚本加载到游戏里执行。因此玩家利用该库即可编写脚本，实现自己想要实现的功能。
