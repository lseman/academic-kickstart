---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Decompositions for mpc of linear dynamic systems with activation constraints
subtitle: ''
summary: ''
authors:
- Pedro Henrique Valderrama Bento da Silva
- Eduardo Camponogara
- Laio Oriel Seman
- Gabriel Villarrubia González
- Valderi Reis Quietinho Leithardt
tags:
- '"Battery charging"'
- '"Benders decomposition"'
- '"EV"'
- '"MPC"'
- '"Outer approximation"'
categories: []
date: '2020-01-01'
lastmod: 2021-08-18T23:20:37-03:00
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
publishDate: '2021-08-19T02:20:37.013020Z'
publication_types:
- '2'
abstract: The interconnection of dynamic subsystems that share limited resources are
  found in many applications, and the control of such systems of subsystems has fueled
  significant attention from scientists and engineers. For the operation of such systems,
  model predictive control (MPC) has become a popular technique, arguably for its
  ability to deal with complex dynamics and system constraints. The MPC algorithms
  found in the literature are mostly centralized, with a single controller receiving
  the signals and performing the computations of output signals. However, the distributed
  structure of such interconnected subsystems is not necessarily explored by standard
  MPC. To this end, this work proposes hierarchical decomposition to split the computations
  between a master problem (centralized component) and a set of decoupled subproblems
  (distributed components) with activation constraints, which brings about organizational
  flexibility and distributed computation. Two general methods are considered for
  hierarchical control and optimization, namely Benders decomposition and outer approximation.
  Results are reported from a numerical analysis of the decompositions and a simulated
  application to energy management, in which a limited source of energy is distributed
  among batteries of electric vehicles.
publication: '*Energies*'
doi: 10.3390/en13215744
---
