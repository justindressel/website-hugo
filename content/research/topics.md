---
date: 2022-04-26
reading_time: false  
share: false  
profile: false  
weight: 10

design:
  spacing:
    padding: ["20px", 0, "20px", 0]
---

# Quantum Computation with Superconducting Qubits

- **Continuous qubit trajectories**\
   In circuit QED we infer the state of a quantum bit (_qubit_) by making a quadrature measurement on an interacting microwave resonator field. Achieving high-fidelity state-tracking from the collected noisy quadrature signal is a necessary prerequisite for more sophisticated quantum information tasks. <br/><br/>
   | {{< figure src="FeedbackCircuit.png" title="Superconducting transmon quantum bits are measured via their dispersive interaction with a neighboring microwave resonator. " >}} |  | {{< figure src="CDRWigner.gif" title="The interaction produces a state-dependent phase shift of a continuous microwave field. This phase shift can be detected as a continuous but noisy voltage signal using a homodyne measurement of the leaked and reflected microwave field." >}} |
   | --- | --- | --- | <br/>
   {{< figure src="RabiTrajectories.png" title="Filtering the noisy voltage signal reconstructs the stochastic quantum state evolution influenced by the continuous observation, known as a quantum trajectory." >}}


- **Quantum feedback and control**\
   One can continuously monitor partial information about a quantum system in order to control experimental parameters in real time for a variety of purposes, such as state purification and initialization, coherence stabilization, and error correction. <br/>\
   {{< cite page="/publication/patti-2017" view="2" >}}


- **Correlated multi-qubit measurement**\
   The expected advantages of quantum computing are rooted in multi-qubit coherence and entanglement effects, with information extracted through uncorrelated high-fidelity projective measurements. A less-explored possibility is exploiting the spatio-temporal correlations between generalized (e.g. weaker) measurements to extract useful information. <br/>\
   {{< cite page="/publication/mohseninia-2019" view="2" >}}


- **Quantum Parameter Estimation**\
   Determining how well one is modeling the physical system in the lab is not a trivial matter. Modern tomographic methods under development use compressive sensing and adaptive estimation techniques to reduce the amount of data that one needs to collect, and reduce the computational resources required to reconstruct the estimates. <br/>\
   {{< cite page="/publication/cortez-2017" view="2" >}}


# Quantum Information and Measurement Theory

- **Quantum instruments**\
  Measurements are a dynamical process in quantum mechanics, best represented as a collection of transformations that are in one-to-one correspondence with the distinguishable results of a physical detector. The information collected by the detector updates the quantum state according to these transformations, which generalize Bayes' rule from classical probability theory. Unlike textbook quantum measurements, the quantum state only partially "collapses" when partial information is collected.  

{{< cite page="/publication/dressel-2013" view="2" >}}


- **Weak Measurements**\
  When almost no information is gathered by a detector making a measurement, the quantum state is almost entirely preserved.  Nevertheless, taking a sufficiently large sample of data still permits the same _average_ infomation to be extracted as textbook projective measurements that fully collapses the state.  

{{< cite page="/publication/white-2016" view="2" >}}


- **Quantum trajectories**\
  Discretizing time into small pieces and applying both natural state evolution and measurement-induced state updates at each time step yields a _quantum trajectory_. Generally these state trajectories show a competition between the natural evolution from the Schroedinger equation and the stochastic evolution from the measurement itself. Stronger measurements per unit time rapidly collapse the state and pin it near the measurement eigenstates, between which _quantum jumps_ can then be tracked. Weaker measurements per unit time minimally perturb the natural evolution, allowing temporal correlations of this _coherent evolution_ to be faithfully extracted.  

{{< cite page="/publication/garcia-pintos-2017" view="2" >}}


- **Conditioned Statistics**\
  Many strange features of quantum mechanics only manifest when several measurements are correlated. Examples include quantum erasure, violations of local realism via Bell inequalities, violations of macrorealism via Leggett-Garg inequalities, anomalously large conditioned averages (including <i>weak values</i>), and even the bunching and anti-bunching behavior of particle statistics.  

{{< cite page="/publication/weber-2014" view="2" >}}



