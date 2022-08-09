---
title: Quantum Information and Measurement Theory
date: 2022-04-26
reading_time: false  
share: false  
profile: false  
weight: 10

design:
  spacing:
    padding: ["20px", 0, "20px", 0]
---

- **Quantum instruments**\
  Measurements are a dynamical process in quantum mechanics, best represented as a collection of transformations that are in one-to-one correspondence with the distinguishable results of a physical detector. The information collected by the detector updates the quantum state according to these transformations, which generalize Bayes' rule from classical probability theory. Unlike textbook quantum measurements, the quantum state only partially "collapses" when partial information is collected.  

{{< cite page="/publication/dressel-2013" view="3" >}}


- **Quantum trajectories**\
  Discretizing time into small pieces and applying both natural state evolution and measurement-induced state updates at each time step yields a quantum trajectory.  Generally these state trajectories show a competition between the natural evolution from the Schroedinger equation and the stochastic evolution from the measurement itself.  

{{< figure src="RabiTrajectories.png" title="Filtering the noisy voltage signal of the leaked microwave field produces stochastic quantum trajectories. [Nature **511**, 570 (2014)]" >}}


- **Weak Measurements**\
  When almost no information is gathered by a detector making a measurement, the quantum state is almost entirely preserved.  Nevertheless, taking a sufficiently large sample of data still permits the same average infomation to be extracted as a textbook measurement that fully collapses the state.  

{{< cite page="/publication/white-2016" view="3" >}}


- **Conditioned Statistics**\
  Many strange features of quantum mechanics only manifest when several measurements are correlated. Examples include quantum erasure, violations of local realism via Bell inequalities, violations of macrorealism via Leggett-Garg inequalities, anomalously large conditioned averages (including <i>weak values</i>), and even the bunching and anti-bunching behavior of particle statistics.  

{{< cite page="/publication/weber-2014" view="3" >}}


