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
date: '2022-04-28'
lastmod: 2022-04-28T00:00:00-00:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  placement: 1
  caption: ''
  focal_point: 'Right'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-04-28T00:00:00.000000Z'
publication_types:
- '2'
abstract: The storage and processing of quantum information are susceptible to external 
  noise, resulting in computational errors. A powerful method to suppress these effects 
  is quantum error correction. Typically, quantum error correction is executed in discrete 
  rounds, using entangling gates and projective measurement on ancillary qubits to complete 
  each round of error correction. Here we use direct parity measurements to implement a 
  continuous quantum bit-flip correction code in a resource-efficient manner, eliminating 
  entangling gates, ancillary qubits, and their associated errors. An FPGA controller actively 
  corrects errors as they are detected, achieving an average bit-flip detection efficiency of 
  up to 91%. Furthermore, the protocol increases the relaxation time of the protected logical 
  qubit by a factor of 2.7 over the relaxation times of the bare comprising qubits. Our 
  results showcase resource-efficient stabilizer measurements in a multi-qubit architecture 
  and demonstrate how continuous error correction codes can address challenges in realizing 
  a fault-tolerant system.
publication: '*Nature Communications* **13**, 2307'
doi: 10.1038/s41467-022-29906-0
url_pdf: papers/s41467-022-29906-0.pdf
links:
- name: Supplement
  url: papers/s41467-022-29906-0.supplement.pdf
- name: arXiv
  url: https://arxiv.org/abs/2107.11398
- name: URL
  url: https://doi.org/10.1038/s41467-022-29906-0
---
