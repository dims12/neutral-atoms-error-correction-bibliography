# Neutral Atoms + Quantum Error Correction — Key Papers

A relevance-ranked reading list on **quantum error correction (QEC) on neutral-atom platforms**,
with a dedicated section on the **Magne** quantum computer's technical lineage (Atom Computing +
Microsoft). Each entry gives authors, venue, citation count, a source link, and the abstract.

> **Scope & sourcing:** Compiled 2026-06-22 via the Semantic Scholar API (relevance ranking +
> citation counts). Citation counts are as of that date and will drift over time. Links point to
> the arXiv abstract page where available, otherwise to the publisher DOI. A few publisher abstracts
> are elided (paywalled) and are flagged accordingly with a brief editorial summary.
> Related: see [`Magne-quantum-computer.md`](./Magne-quantum-computer.md) for the machine overview.

---

## 1. Landmark experimental demonstrations

### Logical quantum processor based on reconfigurable atom arrays
*Bluvstein, Evered, Geim, Li, Zhou, … Greiner, Vuletić, Lukin* — **Nature (2023)** · ~1,455 citations
[arXiv:2312.03982](https://arxiv.org/abs/2312.03982) · [DOI 10.1038/s41586-023-06927-3](https://doi.org/10.1038/s41586-023-06927-3)

> Suppressing errors is the central challenge for useful quantum computing, requiring quantum error
> correction (QEC) for large-scale processing. However, the overhead in the realization of
> error-corrected 'logical' qubits, in which information is encoded across many physical qubits for
> redundancy, poses substantial challenges to large-scale logical quantum computing. Here we report
> the realization of a programmable quantum processor based on encoded logical qubits operating with
> up to 280 physical qubits. Using logical-level control and a zoned architecture in reconfigurable
> neutral-atom arrays, our system combines high two-qubit gate fidelities, arbitrary connectivity, as
> well as fully programmable single-qubit rotations and mid-circuit readout. Operating this logical
> processor with various types of encoding, we demonstrate improvement of a two-qubit logic gate by
> scaling surface-code distance from d = 3 to d = 7, preparation of colour-code qubits with break-even
> fidelities, fault-tolerant creation of logical GHZ states and feedforward entanglement teleportation,
> as well as operation of 40 colour-code qubits. Finally, using 3D [[8,3,2]] code blocks, we realize
> computationally complex sampling circuits with up to 48 logical qubits entangled with hypercube
> connectivity with 228 logical two-qubit gates and 48 logical CCZ gates. We find that this logical
> encoding substantially improves algorithmic performance with error detection, outperforming
> physical-qubit fidelities at both cross-entropy benchmarking and quantum simulations of fast
> scrambling. These results herald the advent of early error-corrected quantum computation and chart a
> path towards large-scale logical processors.

### A fault-tolerant neutral-atom architecture for universal quantum computation
*Bluvstein, Geim, Li, Evered, … Cain, Lukin* — **Nature (2025)** · ~113 citations
[arXiv:2506.20661](https://arxiv.org/abs/2506.20661) · [DOI 10.1038/s41586-025-09848-5](https://doi.org/10.1038/s41586-025-09848-5)

> Quantum error correction (QEC) is essential for the realization of large-scale quantum computers.
> However, owing to the complexity of operating on the encoded 'logical' qubits, understanding the
> physical principles for building fault-tolerant quantum devices and combining them into efficient
> architectures is an outstanding scientific challenge. Here we use reconfigurable arrays of up to 448
> neutral atoms to implement the key elements of a universal, fault-tolerant quantum processing
> architecture and experimentally explore their underlying working mechanisms. We first use surface
> codes to study how repeated QEC suppresses errors, demonstrating 2.14(13)× below-threshold
> performance in a four-round characterization circuit by leveraging atom loss detection and machine
> learning decoding. We then investigate logical entanglement using transversal gates and lattice
> surgery and extend it to universal logic through transversal teleportation with three-dimensional
> [[15,1,3]] codes, enabling arbitrary-angle synthesis with polylogarithmic overhead. Finally, we
> develop mid-circuit qubit reuse, increasing experimental cycle rates by two orders of magnitude and
> enabling deep-circuit protocols with dozens of logical qubits and hundreds of logical teleportations
> with [[7,1,3]] and high-rate [[16,6,4]] codes while maintaining constant internal entropy. Our
> experiments show key principles for efficient architecture design, involving the interplay between
> quantum logic and entropy removal, judiciously using physical entanglement in logic gates and magic
> state generation, and leveraging teleportations for universality and physical qubit reset. These
> results establish foundations for scalable, universal error-corrected processing.

### Fault-tolerant quantum computation with a neutral atom processor ⭐ *(Magne demonstrator)*
*Reichardt, Paetznick, Aasen, … Bloom (Microsoft + Atom Computing)* — **2024** · ~48 citations
[arXiv:2411.11822](https://arxiv.org/abs/2411.11822)

> Quantum computing experiments are transitioning from running on physical qubits to using encoded,
> logical qubits. Fault-tolerant computation can identify and correct errors, and has the potential to
> enable the dramatically reduced logical error rates required for valuable algorithms. However, it
> requires flexible control of high-fidelity operations performed on large numbers of qubits. We
> demonstrate fault-tolerant quantum computation on a quantum processor with 256 qubits, each an
> individual neutral Ytterbium atom. The operations are designed so that key error sources convert to
> atom loss, which can be detected by imaging. Full connectivity is enabled by atom movement. We
> demonstrate the entanglement of 24 logical qubits encoded into 48 atoms, at once catching errors and
> correcting for, on average 1.8, lost atoms. We also implement the Bernstein-Vazirani algorithm with
> up to 28 logical qubits encoded into 112 atoms, showing better-than-physical error rates. In both
> cases, "erasure conversion," changing errors into a form that can be detected independently from
> qubit state, improves circuit performance. These results begin to clear a path for achieving
> scientific quantum advantage with a programmable neutral atom quantum processor.

### Fault-tolerant operation and materials science with neutral atom logical qubits
*Bedalov, Blakely, Buttler, … (Infleqtion)* — **npj Quantum Information (2024)** · ~28 citations
[arXiv:2412.07670](https://arxiv.org/abs/2412.07670) · [DOI 10.1038/s41534-025-01095-w](https://doi.org/10.1038/s41534-025-01095-w)

> We report on the fault-tolerant operation of logical qubits on a neutral atom quantum computer, with
> logical performance surpassing physical performance for multiple circuits including Bell state
> preparation (12× error reduction), random circuits (15×), and a prototype Anderson Impurity Model
> ground state solver for materials science applications (up to 6×, non-fault-tolerantly). The logical
> qubits are implemented via the [[4, 2, 2]] code (C4). Our work constitutes the first complete
> realization of the benchmarking protocol proposed by Gottesman 2016 demonstrating results consistent
> with fault tolerance. In light of recent advances on applying concatenated C4/C6 detection codes to
> achieve error correction with high code rates and thresholds, our work can be regarded as a building
> block towards a practical scheme for fault tolerant quantum computation. Our demonstration of a
> materials science application with logical qubits particularly demonstrates the immediate value of
> these techniques on current experiments.

---

## 2. ⭐ The Magne lineage — Atom Computing / Microsoft path to building it

**Magne** (Denmark / QuNorth) is being built by **Atom Computing** (ytterbium neutral-atom hardware)
with **Microsoft** (Azure software, error correction, decoding). The technical path that makes its
50-logical-qubit target credible runs through the following thread of results:

> **Roadmap in one line:** Engineer *erasure conversion* in metastable ¹⁷¹Yb so that most errors
> become detectable atom-loss/leakage → combine with high-fidelity Rydberg two-qubit gates → encode
> logical qubits whose errors are caught by imaging → scale to the 24-logical-qubit Microsoft/Atom
> Computing demonstrator → deliver **QuNorth's Magne** (50 logical qubits from ~1,225 physical atoms,
> targeted end-2026).

- **Reichardt et al. 2024** — *Fault-tolerant quantum computation with a neutral atom processor*
  (see §1 for the full abstract). The direct Microsoft + Atom Computing demonstrator: 256 Yb atoms,
  24 logical qubits, erasure conversion. [arXiv:2411.11822](https://arxiv.org/abs/2411.11822)

### High-fidelity gates and mid-circuit erasure conversion in an atomic qubit
*Ma, Liu, Peng, Zhang, … Puri, Thompson* — **Nature (2023)** · ~258 citations
[DOI 10.1038/s41586-023-06438-1](https://doi.org/10.1038/s41586-023-06438-1)

> *(Publisher abstract paywalled / elided.)* **Editorial summary:** The foundational experiment
> establishing metastable ¹⁷¹Yb as a fault-tolerance-friendly qubit. It demonstrates high-fidelity
> one- and two-qubit gates and, crucially, *mid-circuit erasure conversion* — detecting the subset of
> gate errors that leak the atom out of the qubit subspace and flagging them as erasures, a much more
> benign error type for QEC. This is the physical mechanism underpinning the Atom Computing / Microsoft
> approach used for Magne.

### High-fidelity gates with mid-circuit erasure conversion in a metastable neutral atom qubit
*Ma, Liu, Peng, Zhang, Jandura, Claes, Burgers, Pupillo, Puri, Thompson* — **2023 (arXiv)** · ~23 citations
[arXiv:2305.05493](https://arxiv.org/abs/2305.05493)

> The development of scalable, high-fidelity qubits is a key challenge in quantum information science.
> Neutral atom qubits have progressed rapidly in recent years, demonstrating programmable processors
> and quantum simulators with scaling to hundreds of atoms. Exploring new atomic species, such as
> alkaline earth atoms, or combining multiple species can provide new paths to improving coherence,
> control and scalability. For example, for eventual application in quantum error correction, it is
> advantageous to realize qubits with structured error models, such as biased Pauli errors or
> conversion of errors into detectable erasures. In this work, we demonstrate a new neutral atom qubit,
> using the nuclear spin of a long-lived metastable state in ¹⁷¹Yb. The long coherence time and fast
> excitation to the Rydberg state allow one- and two-qubit gates with fidelities of 0.9990(1) and
> 0.980(1), respectively. Importantly, a significant fraction of all gate errors result in decays out
> of the qubit subspace, to the ground state. By performing fast, mid-circuit detection of these
> errors, we convert them into erasure errors; during detection, the induced error probability on
> qubits remaining in the computational space is less than 10⁻⁵. This work establishes metastable
> ¹⁷¹Yb as a promising platform for realizing fault-tolerant quantum computing.

### Logical qubits with erasure conversion using metastable neutral atoms
*Zhang, Liu, Bornet, Horvath, Peng, Ma, Huang, Puri, Thompson* — **Nature Physics (2026)**
[DOI 10.1038/s41567-026-03309-0](https://doi.org/10.1038/s41567-026-03309-0)

> *(Publisher abstract paywalled / elided.)* **Editorial summary:** Extends erasure conversion from
> the physical-gate level (Ma et al. 2023) up to the *logical* level — encoding logical qubits in a
> metastable-Yb array where leakage errors are detected and converted to erasures, improving logical
> performance. A direct step on the path from single-qubit erasure demos toward the multi-logical-qubit
> machines of the Magne class.

### Quantum low-density parity-check codes for erasure-biased atomic quantum processors
*Pecorari, Pupillo* — **Physical Review A (2025)** · ~7 citations
[arXiv:2502.20189](https://arxiv.org/abs/2502.20189)

> Identifying the best families of quantum error correction (QEC) codes for near-term experiments is
> key to enabling fault-tolerant quantum computing. Ideally, such codes should have low overhead in
> qubit number, high physical error thresholds, and moderate requirements on qubit connectivity to
> simplify experiments, while allowing for high logical error suppression. Quantum Low-Density
> Parity-Check (LDPC) codes have been recently shown to provide a path towards QEC with low qubit
> overhead and small logical error probabilities. Here, we demonstrate that when the dominant errors
> are erasures — as can be engineered in different quantum computing architectures — quantum LDPC codes
> additionally provide high thresholds and even stronger logical error suppression in parameter regimes
> that are accessible to current experiments. Using large-scale QEC numerical simulations, we benchmark
> the performance of two families of high-rate quantum LDPC codes, namely Clifford-deformed La-cross
> codes and Bivariate Bicycle codes, under a noise model strongly biased towards erasure errors. Both
> codes outperform the surface code by offering up to orders of magnitude lower logical error
> probabilities. Interestingly, we find that this decrease in the logical error probability may not be
> accompanied by an increase in the code threshold, as different QEC codes benefit differently from
> large erasure fractions. While here we focus on neutral atom qubits, the results also hold for other
> quantum platforms, such as trapped ions and superconducting qubits, for which erasure conversion has
> been demonstrated.

---

## 3. Codes, gates & protocols (theory / methods)

### Low-Depth Quantum Error Correction via Three-Qubit Gates in Rydberg Atom Arrays
*Pecorari, Jandura, Pupillo* — **Physical Review Letters (2025)** · ~7 citations
[arXiv:2507.06096](https://arxiv.org/abs/2507.06096)

> Quantum error correction (QEC) requires the execution of deep quantum circuits with large numbers of
> physical qubits to protect information against errors. Designing protocols that can reduce gate and
> space-time overheads of QEC is therefore crucial to enable more efficient QEC in near-term
> experiments. Multiqubit gates offer a natural path toward fast and low-depth stabilizer measurement
> circuits. However, they typically introduce high-weight correlated errors that can degrade the
> circuit-level distance, leading to slower scalings of the logical error probabilities. In this
> Letter, we show how to realize fast and efficient surface code stabilizer readout using only two
> singly controlled Z gates acting simultaneously on two target qubits, i.e., two CZ₂ gates — instead
> of four CZ. We show that this scheme is fault tolerant and provide a blueprint for implementation in
> Rydberg atom arrays. We derive the time-optimal pulses implementing the gates and perform extensive
> QEC numerical simulations with Rydberg decay errors. Compared to the standard protocol using four CZ
> gates, our scheme is faster, uses fewer gates, and crucially maintains fault tolerance with
> comparable logical error probabilities. Fault-tolerant generalizations to biased and
> erasure-dominant noise models, as well as to other QEC codes such as quantum LDPC codes, are also
> discussed.

### Optimized measurement-free and fault-tolerant quantum error correction for neutral atoms
*Veroni, Müller, Giudice* — **Physical Review Research (2024)** · ~21 citations
[arXiv:2404.11663](https://arxiv.org/abs/2404.11663)

> A major challenge in performing quantum error correction (QEC) is implementing reliable measurements
> and conditional feed-forward operations. In quantum computing platforms supporting unconditional
> qubit resets, or a constant supply of fresh qubits, alternative schemes which do not require
> measurements are possible. In such schemes, the error correction is realized via crafted coherent
> quantum feedback. We propose implementations of small measurement-free QEC schemes, which are fault
> tolerant to circuit-level noise. These implementations are guided by several heuristics to achieve
> fault tolerance: redundant syndrome information is extracted, and additional single-shot flag qubits
> are used. By carefully designing the circuit, the additional overhead of these measurement-free
> schemes is moderate compared to their conventional measurement and feed-forward counterparts. We
> highlight how this alternative approach paves the way towards implementing resource-efficient
> measurement-free QEC on neutral-atom arrays.

### Measurement-free quantum error correction optimized for biased noise
*Brechtelsbauer, Butt, Locher, Quintero, Weber, Müller, Büchler* — **2025** · ~7 citations
[arXiv:2505.15669](https://arxiv.org/abs/2505.15669)

> In this paper, we derive optimized measurement-free protocols for quantum error correction and the
> implementation of a universal gate set optimized for an error model that is noise biased. The noise
> bias is adapted for neutral atom platforms, where two- and multi-qubit gates are realized with
> Rydberg interactions and are thus expected to be the dominating source of noise. Careful design of
> the gates allows to further reduce the noise model to Pauli-Z errors. In addition, the presented
> circuits are robust to arbitrary single-qubit gate errors, and we demonstrate that the break-even
> point can be significantly improved compared to fully fault-tolerant measurement-free schemes. The
> obtained logical qubits with their suppressed error rates on logical gate operations can then be used
> as building blocks in a first step of error correction in order to push the effective error rates
> below the threshold of a fully fault-tolerant and scalable quantum error correction scheme.

### Coniq: Enabling Concatenated Quantum Error Correction on Neutral Atom Arrays
*Liu, Xu, Zhou, Wang, Acar, Shi* — **IEEE QCE (2025)** · ~3 citations
[arXiv:2508.05779](https://arxiv.org/abs/2508.05779)

> Recent progress on concatenated codes, especially many-hypercube codes, achieves unprecedented space
> efficiency. Yet two critical challenges persist in practice. First, these codes lack efficient
> implementations of addressable logical gates. Second, the required high degree of parallelism and
> long-range interactions pose significant challenges for current hardware platforms. In this paper, we
> propose an efficient compilation approach for concatenated codes, specifically many-hypercube codes,
> targeted at neutral atom arrays, which provide the necessary parallelism and long-range interactions.
> Our approach builds on two key innovations. First, we introduce Automorphism-assisted Hierarchical
> Addressing (AHA) logical CNOT gates that significantly reduce spacetime overhead compared to
> conventional distillation-based methods. Second, we develop Virtual Atom Intermediate Representation
> (VAIR) that enables level-wise optimization and legalization. We implement these innovations in
> ConiQ, a hardware-aware quantum compiler. Our evaluation demonstrates up to 2000× reduction in
> spacetime overhead and up to 10⁶× reduction in compilation time compared to state-of-the-art
> compilers, with our AHA gates providing an additional overhead reduction of up to 20×. These results
> establish concatenated codes as a promising approach for fault-tolerant quantum computing in the near
> future.

### Bosonic quantum error correction with neutral atoms in optical dipole traps
*Bohnmann, Locher, Zeiher, Müller* — **Physical Review A (2024)** · ~12 citations
[arXiv:2408.14251](https://arxiv.org/abs/2408.14251)

> Bosonic quantum error correction codes encode logical qubits in the Hilbert space of one or multiple
> harmonic oscillators. A prominent class of bosonic codes is that of Gottesman-Kitaev-Preskill (GKP)
> codes of which implementations have been demonstrated with trapped ions and microwave cavities. In
> this paper, we investigate theoretically the preparation and error correction of a GKP qubit in a
> vibrational mode of a neutral atom stored in an optical dipole trap. This platform has recently shown
> remarkable progress in simultaneously controlling the motional and electronic degrees of freedom of
> trapped atoms. The protocols we develop make use of motional states and, additionally, internal
> electronic states of the trapped atom to serve as an ancilla qubit. We compare optical tweezer arrays
> and optical lattices and find that the latter provide more flexible control over the confinement in
> the out-of-plane direction, which can be utilized to optimize the conditions for the implementation
> of GKP codes. Concretely, the different frequency scales that the harmonic oscillators in the axial
> and radial lattice directions exhibit and a small oscillator anharmonicity prove to be beneficial for
> robust encodings of GKP states. Finally, we underpin the experimental feasibility of the proposed
> protocols by numerically simulating the preparation of GKP qubits in an optical lattice with
> realistic parameters.

---

## 4. Architecture & scaling

### Fault-tolerant optical interconnects for neutral-atom arrays
*Sinclair, Ramette, Grinkemeyer, Bluvstein, Lukin, Vuletić* — **Physical Review Research (2024)** · ~50 citations
[arXiv:2408.08955](https://arxiv.org/abs/2408.08955) · [DOI 10.1103/physrevresearch.7.013313](https://doi.org/10.1103/physrevresearch.7.013313)

> We analyze the use of photonic links to enable large-scale fault-tolerant connectivity of locally
> error-corrected modules based on neutral atom arrays. Our approach makes use of recent theoretical
> results showing the robustness of surface codes to boundary noise and combines recent experimental
> advances in atom-array quantum computing with logical qubits with optical quantum networking
> techniques. We find the conditions for fault tolerance can be achieved with local two-qubit Rydberg
> gate and nonlocal Bell-pair errors below 1% and 10%, respectively, without requiring distillation or
> space-time overheads. Realizing the interconnects with a lens, a single optical cavity, or an array
> of cavities enables — with sufficient multiplexing — a Bell-pair generation rate in the 1–50 MHz
> range. When directly interfacing logical qubits, this rate translates to error-correction cycles in
> the 25–2000 kHz range, satisfying all requirements for fault tolerance and in the upper range fast
> enough for 100 kHz logical clock cycles.

### Optimal State Preparation for Logical Arrays on Zoned Neutral Atom Quantum Computers
*Stade, Schmid, Burgholzer, Wille* — **DATE (2025)** · ~8 citations
[arXiv:2411.09738](https://arxiv.org/abs/2411.09738) · [DOI 10.23919/DATE64628.2025.10993241](https://doi.org/10.23919/DATE64628.2025.10993241)

> Quantum computing promises to solve problems previously deemed infeasible. However, high error rates
> necessitate quantum error correction for practical applications. Seminal experiments with zoned
> neutral atom architectures have shown remarkable potential for fault-tolerant quantum computing. To
> fully harness their potential, efficient software solutions are vital. A key aspect of quantum error
> correction is the initialization of physical qubits representing a logical qubit in a highly entangled
> state. This process, known as state preparation, is the foundation of most quantum error correction
> codes. Generating a schedule of target-specific instructions to perform the state preparation is
> highly complex. First software tools exist but are not suitable for the zoned neutral atom
> architectures. This work addresses this gap by leveraging the computational power of SMT solvers and
> generating minimal schedules for the state preparation of logical arrays. Experimental evaluations
> demonstrate that actively utilizing zones to shield idling qubits consistently results in higher
> fidelities than solutions disregarding these zones. The complete code is publicly available in
> open-source as part of the Munich Quantum Toolkit (MQT).

---

## 5. Review & survey papers

### Quantum computing with atomic qubit arrays: confronting the cost of connectivity
*Saffman* — **Review (2025)** · ~15 citations
[arXiv:2505.11218](https://arxiv.org/abs/2505.11218)

> These notes present a review of the status of quantum computing with arrays of neutral atom qubits,
> an approach which has demonstrated remarkable progress in the last few years. Scaling digital quantum
> computing to qubit counts and control fidelities that will enable solving outstanding scientific
> questions, and provide commercial value, is an outstanding challenge, not least because of the
> requirement of connecting and entangling distant qubits. Long-range Rydberg gates and physical motion
> outfit atomic qubit arrays with tools for establishing connectivity. These tools operate on different
> timescales and with distinct levels of parallelization. We analyze several prototypical architectures
> from the perspective of achieving fast connectivity for circuits with large scale entanglement, as
> well as fast cycle times for measurement based quantum error correcting codes. Extending Rydberg
> interactions to multiple atomic species has emerged as a promising route to achieving this latter
> requirement.

### Computational capabilities and compiler development for neutral atom quantum processors
*Schmid, Locher, Rispler, Blatt, Zeiher, Müller, Wille* — **Review, Quantum Sci. Technol. (2023)** · ~44 citations
[arXiv:2309.08656](https://arxiv.org/abs/2309.08656) · [DOI 10.1088/2058-9565/ad33ac](https://doi.org/10.1088/2058-9565/ad33ac)

> Neutral Atom Quantum Computing (NAQC) emerges as a promising hardware platform primarily due to its
> long coherence times and scalability. Additionally, NAQC offers computational advantages encompassing
> potential long-range connectivity, native multi-qubit gate support, and the ability to physically
> rearrange qubits with high fidelity. However, for the successful operation of a NAQC processor, one
> additionally requires new software tools to translate high-level algorithmic descriptions into a
> hardware executable representation, taking maximal advantage of the hardware capabilities. Realizing
> new software tools requires a close connection between tool developers and hardware experts. This work
> aims to provide a basis to establish this connection by investigating the broad spectrum of
> capabilities intrinsic to the NAQC platform and its implications on the compilation process. We first
> review the physical background of NAQC and derive how it affects the overall compilation process by
> formulating suitable constraints and figures of merit. We then provide a summary of the compilation
> process and discuss currently available software tools, and present selected case studies comparing
> two hardware setups.

### Awesome Quantum Computing Experiments: Benchmarking Experimental Progress Towards Fault-Tolerant Quantum Computation
*Le Régent* — **Review (2025)** · ~4 citations
[arXiv:2507.03678](https://arxiv.org/abs/2507.03678) · [GitHub dataset](https://github.com/francois-marie/awesome-quantum-computing-experiments)

> Achieving fault-tolerant quantum computation (FTQC) demands simultaneous progress in physical qubit
> performance and quantum error correction (QEC). This work reviews and benchmarks experimental
> advancements towards FTQC across leading platforms, including trapped ions, superconducting circuits,
> neutral atoms, NV centers, and semiconductors. We analyze key physical metrics like coherence times,
> entanglement error, and system size (qubit count), fitting observed exponential trends to characterize
> multi-order-of-magnitude improvements over the past two decades. At the logical level, we survey the
> implementation landscape of QEC codes, tracking realized parameters [[n, k, d]] and complexity from
> early demonstrations to recent surface and color code experiments. Synthesizing these physical and
> logical benchmarks reveals substantial progress enabled by underlying hardware improvements, while
> also outlining persistent challenges towards scalable FTQC. The experimental databases and analysis
> code underpinning this review are publicly available.

### Neutral atom quantum computers for applications in condensed matter physics
*Shweta, Kaur, Singh, Kanjilal, Santra* — **Review, J. Phys.: Condens. Matter (2025)** · ~1 citation
[DOI 10.1088/1361-648X/adbb9b](https://doi.org/10.1088/1361-648X/adbb9b)

> Quantum computers have the potential to solve problems that are difficult or impossible to address
> using classical modes of computation. Laser cooled neutral atoms at ultracold temperatures offer
> unique possibilities to study interacting many-body quantum systems which is at the heart of various
> quantum condensed matter phenomena. The first-generation neutral atom quantum computers for performing
> special purpose quantum computations was realized by trapping ultracold atoms in optical lattices.
> These tunable and scalable machines provided tremendous opportunities to study various quantum phases
> of Bose and Fermi Hubbard models, topological phases, and non-equilibrium dynamics. In a more recent
> advent, arrays of single neutral atoms trapped in optical tweezers have emerged as a dark horse
> candidate for universal and fault tolerant quantum computing. Here, we review recent advances and
> achievements obtained with this platform and discuss future perspectives.

### Aquila: QuEra's 256-qubit neutral-atom quantum computer (whitepaper)
*Wurtz, Bylinskii, Braverman, … Keesling (QuEra)* — **2023** · ~140 citations
[arXiv:2306.11727](https://arxiv.org/abs/2306.11727)

> The neutral-atom quantum computer "Aquila" is QuEra's latest device available through the Braket cloud
> service on Amazon Web Services (AWS). Aquila is a "field-programmable qubit array" (FPQA) operated as
> an analog Hamiltonian simulator on a user-configurable architecture, executing programmable coherent
> quantum dynamics on up to 256 neutral-atom qubits. This whitepaper serves as an overview of Aquila and
> its capabilities: how it works under the hood, key performance benchmarks, and examples that
> demonstrate some quintessential applications. This includes an overview of neutral-atom quantum
> computing, as well as five examples of increasing complexity from single-qubit dynamics to
> combinatorial optimization, implemented on Aquila. This whitepaper is intended for readers who are
> interested in learning more about neutral-atom quantum computing, as a guide for those who are ready
> to start using Aquila, and as a reference point for its performance as an analog quantum computer.

---

*Compiled via the Semantic Scholar API on 2026-06-22. Citation counts are approximate and current as
of that date.*
