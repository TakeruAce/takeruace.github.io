---
title: Transcalibur
summary: An example of using the in-built project page.
tags:
- research
date: "2018-08-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

# Concepts
The shape of the grasping object as perceived by humans is affected by the moment of inertia of the object and its appearance. In this project, we developed a handheld VR controller "Transcalibur" that can reproduce the sensation of holding various virtual objects by moving the positions of the two weights.

The relationship between the position of the weight and the perceived shape of the device is formulated using a data-driven method to optimize the position of the weight of the device for the appearance of a given virtual object.

# Video
{{<youtube OiSbn6D5kwA>}}

# Hardware 
By moving the two weighted modules in polar coordinates in a two-dimensional plane, Transcalibur changes its own moment of inertia.
{{<figure src="/img/transform.gif">}} 

# Computational Perception Model
In order to generate real sensations with various objects in the virtual environment, it is necessary to know the relationship between the "position of the weight" and the "shape that humans actually perceive".
However, this relationship has not been established as a theory.

Therefore, we collected a large amount of paired data of "actual human shape perception" for Transcalibur's "weight position" and formulated a mathematical model of human shape perception by performing multiple regression analysis.

{{<figure src="/img/approach.png">}} 


# Award
**Honorable Mention** at CHI2019
# Media
[<font color="blue">『ブルーサーマル』的VR超初心者入門漫画 その3＞＞「で、結局のところVRの正体ってなんですか？」</font>](https://cgworld.jp/feature/201810-thermal-03.html) CGWORLD.jp 2018.10
