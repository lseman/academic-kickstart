---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: MPI hardware framework for many-core based embedded systems
subtitle: ''
summary: ''
authors:
- Rodrigo Vinicius Mendonça Pereira
- Laio Oriel Seman
- Marcelo Daniel Berejuck
- Douglas Rossi de Melo
- Analucia Schiaffino Morales
- Eduardo Augusto Bezerra
tags:
- '"Analytical model"'
- '"MPI hardware"'
- '"MPSoC"'
- '"Multiprocessor system-on-chip"'
- '"NOC"'
- '"Network-on-chip"'
- '"Queue model"'
- '"Sensor network"'
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
publishDate: '2021-08-19T02:16:20.186146Z'
publication_types:
- '2'
abstract: This paper presents an investigation and evaluation of the services and
  infrastructure performance of a software and hardware implementation subset of the
  message passing interface (MPI) standard. The proposal for an efficient MPI Hardware
  and MPI Software models, along with the presentation and evaluation of its queuing
  model, aims at giving the system design a framework to assist. Comparative results
  are presented between MPI in hardware and software such as silicon consumption,
  processing time and transfer rate of the system related to the size of buffers.
  Tests in an environment consisting of an MPSoC model integrated on a network-on-chip
  (NoC) were performed, including classical algorithms such as PI calculation and
  the Dining Philosophers problem, to evaluate the proposed model functionality. Experimental
  results demonstrated the effectiveness of the proposed approach and the resulting
  implementation, although this comes at the cost of increased use of silicon in hardware
  implementation.
publication: '*International Journal of Sensor Networks*'
doi: 10.1504/IJSNET.2021.112888
---
