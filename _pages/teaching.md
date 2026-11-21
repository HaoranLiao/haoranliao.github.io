---
layout: page
permalink: /curriculum_vitae/
title: CV
description: 
nav: true
nav_order: 6
---

<!-- For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.

Organize your courses by years, topics, or universities, however you like! -->

#### Skills

* QEC:
  * Experience with circuit-level investigation of FTQC, computing logical error rate;
familiar with CSS formalism; familiar with lattice surgery, code deformation / switching, magic state cultivation / distillation.
* Other:
  * Error mitigation / suppression, Fermionic simulation, Superconducting qubit control, QCVV, Tensor network
* Coding:
  * Stim, Qiskit; Git
 
---

#### Education

* Ph.D. Physics, University of California, Berkeley
<br> Supervisor: K. Birgitta Whaley
<br> Co-supervisor: Irfan Siddiqi
<!--<br> Dissertation: Interplay between quantum computation and machine learning-->
* B.Sc. Honours Mathematics and Physics, McGill University <!--, Montr&#233;al, Qu&#233;bec-->

---

#### Experience
* Senior Research Scientist, Q-CTRL
<br> 02/2024&thinsp;&mdash;&thinsp;Present &nbsp;Los Angeles, United States
  * QEC
    * The first experimental demonstration of magic state cultivation with lattice-surgery escape (improved) from a color code into a surface code, decoded on circuit-level error models calibrated to device noise. Achieved record surface-code magic-state fidelity and per-memory-cycle LER. Extended and completed the alternative magic state cultivation with grafting escape by incorporating a switch into a matchable grafted code. ([arXiv 2026](https://scirate.com/arxiv/2611.22035))
    * Designed and implemented a new protocol for long-range CNOT gates that is currently state-of-the-art, achieving the highest gate fidelity across up to 40+ qubits, leveraging error detection. Leveraged sparse parity checks to enable 75-qubit GHZ state preparation. (<a href="https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.6.020331">PRX Quantum 2025</a>)
  * Improve hardware performance by error suppression/mitigation and compilation
    * I came up with the most efficient compilation of the Fermi-Hubbard model in 1D: the *pair-interleaved* ordering of the fermion-to-qubit mapping together with its fSWAP network, which enabled the deepest large-scale circuit ever executed on quantum hardware. Observed spin-charge separation across coupling regimes, in quantitative agreement with TDVP tensor-network simulations. ([arXiv 2026](https://arxiv.org/pdf/2605.04025))
    * Trotter simulation of a bosonic Hamiltonian on Quantinuum devices with error mitigation. ([arXiv 2026](https://arxiv.org/pdf/2604.14094))
* Research Intern, IBM Quantum
<br> 02/2023&thinsp;&mdash;&thinsp;08/2023 &nbsp;New York, United States
  * Quantum error mitigation and suppression
    * Developed ML-based quantum error mitigation that greatly reduces the cost of traditional methods without sacrificing accuracy on classically intractable circuits, including VQE and tomography-like experiments. (<a href="https://www.nature.com/articles/s42256-024-00927-2">Nat. Mach. Intell. 2024</a>, NeurIPS AI4Science 2023)
    * Designed staggered dynamical decoupling and context-aware compilation absorbing transmon crosstalk into the Hamiltonian in many-body simulations. (<a href="https://ieeexplore.ieee.org/abstract/document/10609605">ISCA 2024</a>)
  * Quantum error characterization
    * Pauli channel estimation via error-mitigated entanglement-enhanced benchmarking, exponentially reducing sampling cost vs. cycle benchmarking. ([Nat. Commun. 2024](https://www.nature.com/articles/s41467-026-75553-0#citeas))

* Ph.D. Student Researcher, UC Berkeley
<br> 09/2018&thinsp;&mdash;&thinsp;12/2023 &nbsp;Berkeley, United States
  * QEC
    * Developed an RNN decoder for continuous quantum error correction that actively corrects errors from noisy dispersive readout of superconducting qubits, robust to real-device non-idealities (auto-correlation, resonator transients, drift). Matched a Bayesian classifier on tasks including quantum annealing. (<a href="https://iopscience.iop.org/article/10.1088/1367-2630/ac66f9/meta">New J. Phys. 2022</a>)
  * Variational algorithms
    * Proved via concentration of measure that the practical adversarial robustness of quantum classifiers decreases only mildly polynomially in the number of qubits, not exponentially as previously believed. (<a href="https://journals.aps.org/pra/abstract/10.1103/PhysRevA.103.042427">Phys. Rev. A 2021</a>)
    * Studied decoherence in tensor network QML models and their connection to Bayesian networks; showed noisy ancillas help mitigate decoherence. (<a href="https://link.springer.com/article/10.1007/s42484-022-00095-9">Quantum Mach. Intell. 2023</a>)
    * Collaborated on showing tensor networks with boundary-law entanglement suit classifying data with similar mutual information scaling. (<a href="https://iopscience.iop.org/article/10.1088/2632-2153/ac44a9/meta">Mach. Learn.: Sci. Technol. 2021</a>)

---

#### Project
- [A straightforward introduction to superconducting qubit control](https://haoranliao.github.io/projects/straightforward_introduction), H. Liao, V. Tripathi 
  <br> An introductory guide to superconducting device physics  with full derivations from the scratch.

---

#### Publications
* <a href="https://scholar.google.com/citations?user=P35A9JoAAAAJ&hl=en">Google Scholar</a>


---

#### Academic Service
- Reviewed for Journals [<a href="https://orcid.org/0000-0002-6399-006X">ORCID</a>, <a href="https://www.webofscience.com/wos/author/record/32106605">WoS</a>] : <br>
  - npj Quantum Information<br>
  - Quantum<br>
  - Quantum Science and Technology<br>
  - New Journal of Physics<br>
  - Journal of Physics A: Mathematical and Theoretical<br>
  - Quantum Machine Intelligence<br>
- <a href="https://accreditations.ioppublishing.org/5f99587a-af12-4bf2-a2ee-7ed54eb065ed#gs.2zkzzo">IOP Trusted Reviewer status</a>
  <br> In recognition of exceptionally high level of peer review competency

---

#### Talks & Seminars
- 09/25,&ensp;IEEE Quantum Week<br>
- 11/24,&ensp;NSF Workshop on Real-Time Control<br>
- 12/23,&ensp;NeurIPS AI4Science Workshop<br>
- 11/23,&ensp;Unitary Fund Seminar<br>
- 10/23,&ensp;Qiskit Seminar<br>
- 09/23,&ensp;IEEE Quantum Week<br>
- 01/22,&ensp;Quantum System Accelerator (QSA) Seminar<br>
- 10/21,&ensp;Quantum Techniques in Machine Learning (QTML)<br>



<!-- - 03/25,&ensp;APS Global Physics Summit<br> -->
<!-- - 03/24,&ensp;APS March Meeting<br> -->
<!-- - 03/22,&ensp;APS March Meeting<br> -->
<!-- - 03/21,&ensp;APS March Meeting<br> -->
---

#### Patents
- 01/24,&ensp;Suppression of correlated noise in quantum computers
- 09/23,&ensp;Performing quantum error mitigation at runtime using trained machine learning model

---

#### Teaching

[//]: # (I led dicussion sessions for the following courses)

UC Berkeley: <br>
- <a href="https://classes.berkeley.edu/content/2023-fall-physics-288-001-lec-001">PHYS 288</a>&nbsp;Bayesian, and ML for Physics, 2023<br>
- <a href="https://classes.berkeley.edu/content/2019-fall-physics-112-001-lec-001">PHYS 112</a>&nbsp;Statistical Mechanics, 2019<br>
- <a href="https://classes.berkeley.edu/content/2019-spring-physics-5b-001-lec-001">PHYS 5B</a>&nbsp;Electromagnetism, Waves, and Optics, 2019<br>
- <a href="https://classes.berkeley.edu/content/2018-fall-physics-7b-001-lec-001">PHYS 7B</a>&nbsp;Physics for Scientists and Engineers, 2018<br>

McGill: <br>
- <a href="https://www.mcgill.ca/study/2016-2017/courses/math-315">MATH 315</a>&nbsp;Differential Equations, 2017<br>
(Awarded Tomlinson Engagement Award for Mentoring)<br>
- <a href="https://www.mcgill.ca/study/2016-2017/courses/math-235">MATH 235</a>&nbsp;Abstract Algebra, 2016<br> 
<!-- - <a href="https://susmcgill.ca/peer-tutoring">Tutor</a> for Mechanics and Calculus, 2015<br> -->

<!--
---

#### Skills
- Quantum information:
  <br> Quantum error mitigation/suppression, Superconducting device physics, Quantum error correction, Quantum error characterization, Open-system dynamics, Quantum machine learning, Tensor network, Quantum measurement and control, Quantum algorithm

- Machine leanring [<a href="https://github.com/HaoranLiao">Github</a>]:
  <br>Traditional/deep ML, Bayesian inference, Deep reinforcement learning, etc. 
<br> Distributed GPU training, Ray Tune, Cloud platform (GCP)

---

#### Courses
* <a href="https://www.linkedin.com/in/haoran-liao/details/courses">List of advanced courses taken</a>
-->

