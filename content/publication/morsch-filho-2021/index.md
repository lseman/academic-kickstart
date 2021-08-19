---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Simulation of a CubeSat with internal heat transfer using Finite Volume Method
subtitle: ''
summary: ''
authors:
- Edemar Morsch Filho
- Laio Oriel Seman
- Vicente de Paulo Nicolau
tags:
- '"CubeSat"'
- '"Finite Volume Method"'
- '"Gebhart method"'
- '"Internal heat transfer"'
- '"Obstruction"'
- '"Temperature simulation"'
categories: []
date: '2021-01-01'
lastmod: 2021-08-18T23:16:20-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-08-19T02:16:20.618212Z'
publication_types:
- '2'
abstract: 'Estimating temperature is essential both to design reliable CubeSats and
  to keep it under maximum operating efficiency. This paper presents the transient
  thermal simulation of a CubeSat 1U, where the heat transfer by conduction and radiation
  (external and internal) are solved considering a typical CubeSat mission launched
  from the International Space Station. The objective is to obtain the temperature
  field based on the Finite Volume Method (FVM), with inner heat transfer by radiation.
  The Gebhart method computes the internal heat exchange through successive reflections,
  and an obstruction model supports the calculation of view factors. Three boundary
  conditions for the inner side of the CubeSat are tested: without internal heat transfer
  by radiation, or zero emissivity (ϵ=0.0), with intermediate internal heat transfer
  by radiation (ϵ=0.5), and maximum internal heat transfer by radiation (ϵ=1.0). The
  results show a significant impact of the internal heat transfer by radiation in
  the temperature field of both inner and outer parts of the satellite, and therefore
  it should not be ignored. Good agreement of transient temperature is found between
  the FVM and another more straightforward formulation based on the Lumped Method,
  although the three-dimensional effects are significant and cannot be obtained with
  such a simplified model.'
publication: '*Applied Thermal Engineering*'
doi: 10.1016/j.applthermaleng.2021.117039
---
