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
  * Experience with analytical and numerical circuit-level investigation of QEC and FTQC, computing logical error rate;
familiar with FT Steane code, surface code; familiar with FT gadgets, lattice surgery, magic state cultivation.
* Coding:
  * Qiskit, Stim, Git
* Other:
  * Error mitigation/suppression, Superconducting qubit control, Fermionic simulation, QCVV, Tensor network

#### Education

* Ph.D. Physics, University of California, Berkeley
<br> Supervisor: K. Birgitta Whaley
<!--<br> Dissertation: Interplay between quantum computation and machine learning-->
* B.Sc. Honours Mathematics and Physics, McGill University <!--, Montr&#233;al, Qu&#233;bec-->

---

#### Experience
* Senior Research Scientist, Q-CTRL
<br> 02/2024&ndash;&ndash;Present &nbsp;Los Angeles, United States
  * QEC-related research and demonstration
    * Investigating magic state cultivation on superconducting hardware, and more superconducting hardware friendly FT implementation of Steane code.
    * Designed and implemented a new protocol for long-range CNOT gates that is currently state-of-the-art, achieving the highest gate fidelity across up to 40+ qubits, leveraging error detection. Leveraged sparse parity checks to enable 75-qubit GHZ state preparation. (<a href="https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.6.020331">PRX Quantum 2025</a>)
  * Improve hardware performance by error detection/suppression/mitigation and compilation
    * Improved simulation of Fermi-Hubbard-like model in 1D and 2D on IBM hardware with more depth-efficient compilation, also enabling research on unexplored physics.
    * Simulating high-energy physics model on ion-trapped devices with error detection and error mitigation. ([arXiv 2026](https://arxiv.org/pdf/2604.14094))
* Research Intern, IBM Quantum
<br> 02/2023&ndash;&ndash;08/2023 &nbsp;New York, United States
  * Develop novel quantum error mitigation and error suppression techniques
    * Developed a machine learning-based quantum error mitigation technique that significantly reduces the cost of traditional quantum error mitigation methods without sacrificing accuracy on classically intractable circuits. Showed its superiority for variational algorithms such as VQE, and tomography-like experiments. (<a href="https://www.nature.com/articles/s42256-024-00927-2">Nat. Mach. Intell. 2024</a>, NeuIPS AI4Science 2023)
    * Crosstalk suppression by context-aware compilation absorbing transmon crosstalk into the Hamiltonian in many-body physics simulations. (<a href="https://ieeexplore.ieee.org/abstract/document/10609605">Proceedings of ISCA 2024</a>)
  * Quantum error characterization
    * Pauli channel estimation using error-mitigated entanglement-enhanced benchmarking, exponentially reducing sampling complexity compared to cycle benchmarking. (<a href="https://arxiv.org/abs/2408.03376">arXiv 2024</a>)

* Ph.D. Student Researcher, UC Berkeley
<br> 09/2018&ndash;&ndash;12/2023 &nbsp;Berkeley, United States
  * QEC
    * Developed a protocol for continuous quantum error correction on dispersive readout signals on superconducting qubits. The protocol decodes and applies active corrections. Benchmarked against Bayesian inference model on tasks including quantum annealing. (<a href="https://iopscience.iop.org/article/10.1088/1367-2630/ac66f9/meta">New J. Phys. 2022</a>)
  * Variational algorithms
    * Derived the robustness of general quantum classifiers against worst-case input perturbations based on concentration of measure phenomenon. Proved that the practical robustness of generic quantum classifiers decreases only mildly polynomially in the number of qubits, in contrast to the extreme vulnerability previously believed. (<a href="https://journals.aps.org/pra/abstract/10.1103/PhysRevA.103.042427">Phys. Rev. A 2021</a>)
    * Analytically and numerically studied decoherence in tensor network discriminative QML models and their connections to classical Bayesian networks. Showed that adding noisy ancillas helps mitigate decoherence in simulations with distributed GPU training. (<a href="https://link.springer.com/article/10.1007/s42484-022-00095-9">Quantum Mach. Intell. 2023</a>)
    * Collaborated on showing tensor networks with boundary-law entanglement entropy are suitable for classifying datasets with similar mutual information scaling. (<a href="https://iopscience.iop.org/article/10.1088/2632-2153/ac44a9/meta">Mach. Learn.: Sci. Technol. 2021</a>)


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
- 12/23,&ensp;NeuIPS AI4Science Workshop<br>
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

