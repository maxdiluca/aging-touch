---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'PrendoSim: Proxy-Hand-Based Robot Grasp Generator'
subtitle: ''
summary: ''
authors:
- Diar Abdlkarim
- Valerio Ortenzi
- Tommaso Pardi
- Maija Filipovica
- Alan Wing
- Katherine J Kuchenbecker
- Massimiliano Di Luca
tags:
- 'robot grasping'
- 'simulation'
- 'virtual environment'
- 'virtual reality'
- 'robotics'
categories: []
date: '2021-01-01'
lastmod: 2021-04-16T20:49:04+02:00
featured: true
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
publishDate: '2021-04-16T18:49:03.909854Z'
publication_types:
- '1'
abstract: The synthesis of realistic robot grasps in a simulated environment is pivotal in generating datasets that support sim-to-real transfer learning. In a step toward achieving this goal, we propose PrendoSim, an open-source grasp generator based on a proxy-hand simulation that employs NVIDIA's physics engine (PhysX) and the recently released articulated-body objects developed by Unity (https://prendosim.github.io). We present the implementation details, the method used to generate grasps, the approach to operationally evaluate stability of the generated grasps, and examples of grasps obtained with two different grippers (a parallel jaw gripper and a three-finger hand) grasping three objects selected from the YCB dataset (hammer, screwdriver, and scissors).  Compared to simulators proposed in the literature, PrendoSim balances grasp realism and ease of use, displaying an intuitive interface and enabling the user to produce a large and varied dataset of stable grasps.
publication: '*ICINCO 2021*'
url_code: https://prendosim.github.io
---
