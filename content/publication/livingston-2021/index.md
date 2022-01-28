---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Experimental demonstration of continuous quantum error correction
subtitle: ''
summary: ''
authors:
- William P Livingston
- Machiel S Blok
- Emmanuel Flurin
- Justin Dressel
- Andrew N Jordan
- Irfan Siddiqi
tags: []
categories: []
date: '2021-07-01'
lastmod: 2022-01-25T16:51:27-08:00
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
publishDate: '2022-01-28T00:18:21.434077Z'
publication_types:
- '3'
abstract: The storage and processing of quantum information are susceptible to external
  noise, resulting in computational errors that are inherently continuous A powerful
  method to suppress these effects is to use quantum error correction. Typically,
  quantum error correction is executed in discrete rounds where errors are digitized
  and detected by projective multi-qubit parity measurements. These stabilizer measurements
  are traditionally realized with entangling gates and projective measurement on ancillary
  qubits to complete a round of error correction. However, their gate structure makes
  them vulnerable to errors occurring at specific times in the code and errors on
  the ancilla qubits. Here we use direct parity measurements to implement a continuous
  quantum bit-flip correction code in a resource-efficient manner, eliminating entangling
  gates, ancilla qubits, and their associated errors. The continuous measurements
  are monitored by an FPGA controller that actively corrects errors as they are detected.
  Using this method, we achieve an average bit-flip detection efficiency of up to
  91%. Furthermore, we use the protocol to increase the relaxation time of the protected
  logical qubit by a factor of 2.7 over the relaxation times of the bare comprising
  qubits. Our results showcase resource-efficient stabilizer measurements in a multi-qubit
  architecture and demonstrate how continuous error correction codes can address challenges
  in realizing a fault-tolerant system.
publication: ''
links:
- name: arXiv
  url: https://arxiv.org/abs/2107.11398
---
