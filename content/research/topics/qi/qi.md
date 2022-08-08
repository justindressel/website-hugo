---
title: Quantum Information and Computation
date: 2022-04-26
reading_time: false  
share: false  
profile: false  
weight: 10

---

## Quantum computing with superconducting qubits

{{< figure src="RabiTrajectories.png" title="Superconducting transmon quantum bits are measured via their dispersive interaction with a neighboring microwave resonator. The interaction produces a state-dependent phase shift of a continuous microwave field, which can be detected as a continuous but noisy voltage signal using a homodyne measurement of the reflected microwave field. This continuous noisy voltage produces stochastic quantum trajectories, which have rich statistics. [Nature **511**, 570 (2014)]" >}}

- **Continuous qubit trajectories**\
  In circuit QED we infer the state of a quantum bit (<i>qubit</i>) by making a quadrature measurement on an interacting microwave resonator field. Achieving high-fidelity state-tracking from the collected noisy quadrature signal is a necessary prerequisite for more sophisticated quantum information tasks.  
- **Quantum feedback and control**\
  One can continuously monitor partial information about a quantum system in order to control experimental parameters in real time for a variety of purposes, such as state purification and initialization, coherence stabilization, and error correction.  
- **Correlated multi-qubit measurement**\
  The expected advantages of quantum computing are rooted in multi-qubit coherence and entanglement effects, with information extracted through uncorrelated high-fidelity projective measurements. A less-explored possibility is exploiting the correlations between simultaneous continuous records to extract useful information.  
- **Quantum Parameter Estimation**\
  Determining how well one is modeling the physical system in the lab is not a trivial matter. Modern tomographic methods under development use compressive sensing and adaptive estimation techniques to reduce the amount of data that one needs to collect, and reduce the computational resources required to reconstruct the estimates.  

## Quantum measurement theory
{{< figure src="npjqi201322-f1.png" title="The high-fidelity control enabled by modern superconducting quantum circuits permits interesting extensions to foundational tests of quantum mechanics. In this case, a single ensemble of entangled pairs is probed with a combination of (tunably) weak measurements and strong projective measurements to construct correlators that violate inequality bounds set by locally realistic hidden variable models [npj Quantum Information <b>2</b>, 15022 (2016)]. The experimental circuit uses four fully controllable Xmon qubits developed by the team at UCSB/Google." >}}

- **Quantum instruments**\
  Measurements are a dynamical process in quantum mechanics, best represented as a collection of transformations that are in one-to-one correspondence with the distinguishable results of a physical detector. The information collected by the detector updates the quantum state according to these transformations, which generalize Bayes' rule from classical probability theory. Unlike textbook quantum measurements, the quantum state only partially "collapses" when partial information is collected.  
- **Quantum trajectories**\
  Discretizing time into small pieces and applying both natural state evolution and measurement-induced state updates at each time step yields a quantum trajectory.  Generally these state trajectories show a competition between the natural evolution from the Schroedinger equation and the stochastic evolution from the measurement itself.  
- **Weak Measurements**\
  When almost no information is gathered by a detector making a measurement, the quantum state is almost entirely preserved.  Nevertheless, taking a sufficiently large sample of data still permits the same average infomation to be extracted as a textbook measurement that fully collapses the state.  
- **Conditioned Statistics**\
  Many strange features of quantum mechanics only manifest when several measurements are correlated. Examples include quantum erasure, violations of local realism via Bell inequalities, violations of macrorealism via Leggett-Garg inequalities, anomalously large conditioned averages (including <i>weak values</i>), and even the bunching and anti-bunching behavior of particle statistics.  


