+++
title = "Publications"
hascode = true
+++
@def tags = ["publications", "papers"]

# List of Publications

\toc

## Radio-Frequency Sweeps at μT Fields for Parahydrogen-Induced Polarization of Biomolecules
[arXiv](https://arxiv.org/abs/2205.15709)

Magnetic resonance imaging of $^{13}$C-labeled metabolites enhanced by parahydrogen-induced polarization (PHIP) can enable real-time monitoring of processes within the body. We introduce a robust, easily implementable technique for transferring parahydrogen-derived singlet order into $^{13}$C magnetization using adiabatic radio-frequency sweeps at μT fields. We experimentally demonstrate the applicability of this technique to several molecules, including some molecules relevant for metabolic imaging, where we show significant improvements in the achievable polarization, in some cases reaching above 60%. Furthermore, we introduce a site-selective deuteration scheme, where deuterium is included in the coupling network of a pyruvate ester to enhance the efficiency of the polarization transfer. These improvements are enabled by the fact that the transfer protocol avoids relaxation induced by strongly coupled quadrupolar nuclei.

## Power-law scaling of correlations in statistically polarised nano-NMR
[arXiv](https://arxiv.org/abs/2203.11161)
<!-- ~~~ -->
<!-- <a href="https://arxiv.org/abs/2203.11161"><img src="/assets/arxivlogo.png" width="45" height="100"></a> -->
<!-- ~~~ -->

Nano-scale nuclear magnetic resonance with NV centres heralds a paradigm shift in biosensing, but its success has been so far prevented by diffusion broadening of spectral features, which hinders the ability to resolve frequencies in spectral measurements. The problem is a direct consequence of the widely accepted assumption that nuclear spin signal correlations decay exponentially in nano-NMR. However, a more accurate analysis of diffusion shows that correlations survive for a longer time due to a power-law scaling, yielding the possibility for improved resolution. Nevertheless, such behaviour remains to be demonstrated in experiments. Using three different experimental setups and disparate measurement techniques, we present overwhelming evidence of power-law decay of correlations. These result in sharp-peaked spectral lines, potentially allowing for improved resolution even in the presence of diffusion broadening.


## Supercharging Quantum Optimal Control with Efficient Automatic Differentiation
[APS](https://meetings.aps.org/Meeting/MAR22/Session/Y41.7)

Numerical optimal control theory has proven an essential tool for achieving a core requirement of both quantum information and quantum metrology: the creation of particular non-classical states, respectively of quantum processes that produce such states. Finding the most general solutions to the relevant control problems would require the direct optimization of, e.g., measures for entanglement, spin squeezing, or the quantum Fisher information. To date, such measures have generally not been considered suitable for optimal control due to the lack of an analytic derivative. We show how the use of automatic differentiation (AD) allows to directly optimize these non-classical measures, and virtually any other functional.  We further show how AD can be **combined** with existing numerical techniques of quantum control to allow the formulation of a "semi-automatic differentiation"''" approach that eliminates the often exponential overhead associated with previous attempts to use AD in quantum control. Thus, our methods scale to large Hilbert space dimensions and open quantum systems. We illustrate the use of the technique for the optimization of entangling quantum gates and the creation of spin-squeezed states.

The proposed methods are realized in a new open-source software framework for numerical quantum control, QuantumControl.jl, written in the Julia language. Designed for extensibility and performance, the framework consists of a collection of packages that implement a wide variety of control algorithms, including Krotov's method, several variations of gradient-ascent methods (GRAPE, GROUP, GOAT), and gradient-free methods such a CRAB. These are enhanced with methods of automatic differentiation for unparalleled flexibility.

## Hyperpolarized solution-state NMR spectroscopy with optically polarized crystals
[JACS](https://pubs.acs.org/doi/abs/10.1021/jacs.1c09119)

Nuclear spin hyperpolarization provides a promising route to overcome the challenges imposed by the limited sensitivity of nuclear magnetic resonance. Here we demonstrate that dissolution of spin-polarized pentacene-doped naphthalene crystals enables transfer of polarization to target molecules via intermolecular cross-relaxation at room temperature and moderate magnetic fields (1.45 T). This makes it possible to exploit the high spin polarization of optically polarized crystals, while mitigating the challenges of its transfer to external nuclei. With this method, we inject the highly polarized mixture into a benchtop NMR spectrometer and observe the polarization dynamics for target 1H nuclei. Although the spectra are radiation damped due to the high naphthalene magnetization, we describe a procedure to process the data to obtain more conventional NMR spectra and extract the target nuclei polarization. With the entire process occurring on a time scale of 1 min, we observe NMR signals enhanced by factors between −200 and −1730 at 1.45 T for a range of small molecules.

## Preferential Placement of Aligned Nitrogen Vacancy Centers in Chemical Vapor Deposition Overgrown Diamond Microstructures
[PSS](https://onlinelibrary.wiley.com/doi/full/10.1002/pssr.202100373)

The usefulness of nitrogen vacancy (NV) centers in diamond is augmented by a low defect and impurity density in the surrounding host material, and applications benefit from the ability to control the position of the NV centers. Herein, a process to create NV centers on single-crystalline diamond microstructures by chemical vapor deposition (CVD) is presented. Pyramidal structures with {111} side facets are formed during the intrinsic overgrowth of dry chemically etched cylindrical pillars on a substrate with {100} surface orientation. A thin nitrogen-doped epitaxial layer is deposited on top of the pyramids resulting in the creation of NV centers exclusively on the {111} pyramid side faces. Optically detected magnetic resonance (ODMR) and spin echo measurements reveal preferential alignment of the NV centers in a single {111} direction and a $T_2$ time of 55 μs. The $T_2$ time of the NV centers is limited by the surrounding substitutional nitrogen (P1 center) concentration of  [P1] = 5 ppm. A low density of other paramagnetic spin noise is detected by double-electron electron resonance (DEER) measurements.

## Macroscopic Hyperpolarization Enhanced with Quantum Optimal Control
[arXiv](https://arxiv.org/abs/2112.15021)

Hyperpolarization of nuclear spins enhances nuclear magnetic resonance signals, which play a key role for imaging and spectroscopy in the natural and life sciences. This signal amplification unlocks previously inaccessible techniques, such as metabolic imaging of cancer cells. In this work, electron spins from the photoexcited triplet state of pentacene-doped naphthalene crystals are used to polarize surrounding protons. As existing strategies are rendered less effective by experimental constraints, they are replaced with optimal control pulses designed with RedCRAB. In contrast to previous optimal control approaches, which consider an average single nucleus, this closed-loop optimization is macroscopic. A 28% improvement in signal and 15% faster polarization rate is observed. Additionally, a strategy called Autonomously-optimized Repeated Linear Sweep (ARISE) is introduced to efficiently tailor existing hyperpolarization sequences in the presence of experimental uncertainty to enhance their performance. ARISE is expected to be broadly applicable in many experimental settings.
