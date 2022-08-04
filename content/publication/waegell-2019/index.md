---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Benchmarks of nonclassicality for qubit arrays
subtitle: ''
summary: ''
authors:
- Mordecai Waegell
- Justin Dressel
tags: []
categories: []
date: '2019-08-01'
lastmod: 2022-01-25T16:51:29-08:00
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
publishDate: '2022-01-28T00:18:22.901323Z'
publication_types:
- '2'
abstract: We present a set of practical benchmarks for N-qubit arrays that economically
  test the fidelity of achieving multi-qubit nonclassicality. The benchmarks are measurable
  correlators similar to 2-qubit Bell correlators, and are derived from a particular
  set of geometric structures from the N-qubit Pauli group. These structures prove
  the Greenberger-Horne-Zeilinger (GHZ) theorem, while the derived correlators witness
  genuine N-partite entanglement and establish a tight lower bound on the fidelity
  of particular stabilizer state preparations. The correlators need only M≤N+1 distinct
  measurement settings, as opposed to the 2^(2N)−1 settings that would normally be
  required to tomographically verify their associated stabilizer states. We optimize
  the measurements of these correlators for a physical array of qubits that can be
  nearest-neighbor-coupled using a circuit of controlled-Z gates with constant gate
  depth to form N-qubit linear cluster states. We numerically simulate the provided
  circuits for a realistic scenario with N=3,...,9 qubits, using ranges of T1 energy
  relaxation times, T2 dephasing times, and controlled-Z gate-fidelities consistent
  with Google's 9-qubit superconducting chip. The simulations verify the tightness
  of the fidelity bounds and witness nonclassicality for all nine qubits, while also
  showing ample room for improvement in chip performance.
publication: '*npj Quantum Information* **5**, 66'
doi: 10.1038/s41534-019-0181-8
url_pdf: papers/npjqi2019.5.66.pdf
links:
- name: Supplement
  url: papers/npjqi2019.5.66.supplement.pdf
- name: arXiv
  url: https://arxiv.org/abs/1812.07821
- name: URL
  url: https://www.nature.com/articles/s41534-019-0181-8
---
