---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Monitoring fast superconducting qubit dynamics using a neural network
subtitle: ''
summary: ''
authors:
- Gerwin Koolstra
- Noah Stevenson
- Shiva Barzili
- Lucas Burns
- Karthik Siva
- Sacha Greenfield
- William Livingston
- Akel Hashim
- Ravi K Naik
- John M Kreikebaum
- Kevin P O'Brien
- David I Santiago
- Justin Dressel
- Irfan Siddiqi
tags: []
categories: []
date: '2022-07-26'
lastmod: 2022-07-26T00:00:00-00:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'BottomRight'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-07-26T00:00:00.000000Z'
publication_types:
- '2'
abstract: Weak measurements of a superconducting qubit produce noisy voltage signals 
  that are weakly correlated with the qubit state. To recover individual quantum trajectories 
  from these noisy signals, traditional methods require slow qubit dynamics and substantial 
  prior information in the form of calibration experiments. Monitoring rapid qubit dynamics, 
  e.g., during quantum gates, requires more complicated methods with increased demand for 
  prior information. Here, we experimentally demonstrate an alternative method for accurately 
  tracking rapidly driven superconducting qubit trajectories that uses a long short-term memory 
  (LSTM) artificial neural network with minimal prior information. Despite few training 
  assumptions, the LSTM produces trajectories that include qubit-readout resonator correlations 
  due to a finite detection bandwidth. In addition to revealing rotated measurement eigenstates 
  and a reduced measurement rate in agreement with theory for a fixed drive, the trained LSTM 
  also correctly reconstructs evolution for an unknown drive with rapid modulation. Our work 
  enables new applications of weak measurements with faster or initially unknown qubit dynamics, 
  such as the diagnosis of coherent errors in quantum gates.
publication: '*Physical Review X* **12**, 031017 (2022)'
doi: 10.1103/PhysRevX.12.031017
url_pdf: papers/PhysRevX.12.031017.pdf
links:
- name: arXiv
  url: https://arxiv.org/abs/2108.12023
- name: URL
  url: https://doi.org/10.1103/PhysRevX.12.031017
---
