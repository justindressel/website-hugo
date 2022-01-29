---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Quantum State Estimation and Tracking for Superconducting Processors Using Machine Learning'
subtitle: ''
summary: ''
authors:
- Shiva Barzili
tags: []
categories: []
date: '2021-12-01'
lastmod: 2022-01-28T15:51:39-08:00
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
publishDate: '2022-01-28T00:18:32.961122Z'
publication_types:
- '7'
abstract: "Quantum technology has been rapidly growing; in particular, the experiments that have been performed with superconducting qubits and circuit QED have allowed us to explore the light-matter interaction at its most fundamental level. The study of coherent dynamics between two-level systems and resonator modes can provide insight into fundamental aspects of quantum physics, such as how the state of a system evolves while being continuously observed. To study such an evolving quantum system, experimenters need to verify the accuracy of state preparation and control since quantum systems are very fragile and sensitive to environmental disturbance. In this thesis, I look at these continuous monitoring and state estimation problems from a modern point of view. With the help of machine learning techniques, it has become possible to explore regimes that are not accessible with traditional methods: for example, tracking the state of a superconducting transmon qubit continuously with dynamics fast compared with the detector bandwidth. These results open up a new area of quantum state tracking, enabling us to potentially diagnose errors that occur during quantum gates. In addition, I investigate the use of supervised machine learning, in the form of a modified denoising autoencoder, to simultaneously remove experimental noise while encoding one and two-qubit quantum state estimates into a minimum number of nodes within the latent layer of a neural network. I automate the decoding of these latent representations into positive density matrices and compare them to similar estimates obtained via linear inversion and maximum likelihood estimation. Using a superconducting multiqubit chip, I experimentally verify that the neural network estimates the quantum state with greater fidelity than either traditional method. Furthermore, the network can be trained using only product states and still achieve high fidelity for entangled states. This simplification of the training overhead permits the network to aid experimental calibration, such as the diagnosis of multi-qubit crosstalk. As quantum processors increase in size and complexity, I expect automated methods such as those presented in this thesis to become increasingly attractive."
publication: '*Ph.D. Thesis: Chapman University*'
url_pdf: papers/barzili-2021-thesis.pdf
links:
- name: URL
  url: https://digitalcommons.chapman.edu/cads_dissertations/26/
---
