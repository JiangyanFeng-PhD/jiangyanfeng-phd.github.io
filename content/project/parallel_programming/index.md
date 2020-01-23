---
title: Optimization of Neural Network Convolution Layer through Parallel Programming
summary: We employed parallel programming optimization approaches for designing and implementing an optimized neural network convolution layer. 
tags:
- GPU
- Parallel Programming
- CUDA
date: "2019-12-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/feng_jf8
- icon: github
  icon_pack: fab
  name: Code Available
  url: https://github.com/JiangyanFeng-PhD/Applied_Parallel_Programming/tree/master/ece408_project
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
We employed parallel programming optimization approaches for designing and implementing an optimized neural network convolution layer.

There are four major optimizations:
1. Kernel fusion.
2. Optimizing grid and block dimensions.
3. Unrolling the for loop using restrict and pragma unroll.
4. Optimizing tile width for tiled matrix multiplication.
