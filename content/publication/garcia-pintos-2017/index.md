---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Past observable dynamics of a continuously monitored qubit
subtitle: ''
summary: ''
authors:
- Luis Pedro Garcia-Pintos
- Justin Dressel
tags: []
categories: []
date: '2017-12-01'
lastmod: 2022-01-25T16:51:31-08:00
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
publishDate: '2022-01-28T00:18:24.815441Z'
publication_types:
- '2'
abstract: Monitoring a quantum observable continuously in time produces a stochastic
  measurement record that noisily tracks the observable. For a classical process such
  noise may be reduced to recover an average signal by minimizing the mean squared
  error between the noisy record and a smooth dynamical estimate. We show that for
  a monitored qubit this usual procedure returns unusual results. While the record
  seems centered on the expectation value of the observable during causal generation,
  examining the collected past record reveals that it better approximates a moving-mean
  Gaussian stochastic process centered at a distinct (smoothed) observable estimate.
  We show that this shifted mean converges to the real part of a generalized weak
  value in the time-continuous limit without additional postselection. We verify that
  this smoothed estimate minimizes the mean squared error even for individual measurement
  realizations. We go on to show that if a second observable is weakly monitored concurrently,
  then that second record is consistent with the smoothed estimate of the second observable
  based solely on the information contained in the first observable record. Moreover,
  we show that such a smoothed estimate made from incomplete information can still
  outperform estimates made using full knowledge of the causal quantum state.
publication: '*Physical Review A* **96**, 062110'
doi: 10.1103/PhysRevA.96.062110
url_pdf: papers/PhysRevA.96.062110.pdf
links:
- name: arXiv
  url: https://arxiv.org/abs/1708.04362
- name: URL
  url: https://link.aps.org/doi/10.1103/PhysRevA.96.062110
---
