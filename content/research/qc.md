---
title: Quantum Computation with Superconducting Qubits
date: 2022-04-26
reading_time: false  
share: false  
profile: false  
weight: 10

design:
  spacing:
    padding: ["20px", 0, "20px", 0]
---

- **Continuous qubit trajectories**\
    In circuit QED we infer the state of a quantum bit (_qubit_) by making a quadrature measurement on an interacting microwave resonator field. Achieving high-fidelity state-tracking from the collected noisy quadrature signal is a necessary prerequisite for more sophisticated quantum information tasks. <br/><br/>
     

| {{< figure src="FeedbackCircuit.png" title="Superconducting transmon quantum bits are measured via their dispersive interaction with a neighboring microwave resonator." height="200px" >}} | {{< figure src="CDRWigner.gif" title="The interaction produces a state-dependent phase shift of a continuous microwave field. This phase shift can be detected as a continuous but noisy voltage signal using a homodyne measurement of the leaked and reflected microwave field." height="200px" >}} |  
| --- | --- |  

<br/>
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


- **Machine Learning for Device Characterization**\
    As chips become more complex in the laboratory, calibration and tune-up becomes an increasingly daunting task. Modern machine learning methods offer novel solutions for auto-calibrating device parameters and tracking dynamics occuring during a computational run. <br/>\
    {{< cite page="publication/koolstra-2022" view="2" >}}

