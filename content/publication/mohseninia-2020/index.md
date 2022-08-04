---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Always-On Quantum Error Tracking with Continuous Parity Measurements
subtitle: ''
summary: ''
authors:
- Razieh Mohseninia
- Jing Yang
- Irfan Siddiqi
- Andrew N Jordan
- Justin Dressel
tags: []
categories: []
date: '2020-11-04'
lastmod: 2022-01-28T14:51:29-08:00
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
publishDate: '2022-01-28T00:18:22.605789Z'
publication_types:
- '2'
abstract: We investigate quantum error correction using continuous parity measurements to correct bit-flip errors with the three-qubit code. Continuous monitoring of errors brings the benefit of a continuous stream of information, which facilitates passive error tracking in real time. It reduces overhead from the standard gate-based approach that periodically entangles and measures additional ancilla qubits. However, the noisy analog signals from continuous parity measurements mandate more complicated signal processing to interpret syndromes accurately. We analyze the performance of several practical filtering methods for continuous error correction and demonstrate that they are viable alternatives to the standard ancilla-based approach. As an optimal filter, we discuss an unnormalized (linear) Bayesian filter, with improved computational efficiency compared to the related Wonham filter introduced by Mabuchi [New J. Phys. 11, 105044 (2009)]. We compare this optimal continuous filter to two practical variations of the simplest periodic boxcar-averaging-and-thresholding filter, targeting real-time hardware implementations with low-latency circuitry. As variations, we introduce a non-Markovian ``half-boxcar'' filter and a Markovian filter with a second adjustable threshold; these filters eliminate the dominant source of error in the boxcar filter, and compare favorably to the optimal filter. For each filter, we derive analytic results for the decay in average fidelity and verify them with numerical simulations.
publication: '*Quantum* **4**, 358'
doi: 10.22331/q-2020-11-04-358
url_pdf: papers/q-2020-11-04-358.pdf
links:
- name: arXiv
  url: https://arxiv.org/abs/1907.08882
- name: URL
  url: https://doi.org/10.22331/q-2020-11-04-358
---
