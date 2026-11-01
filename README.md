# Acoustic Biophysics, Neurocognitive Architecture, and Generative Computation in Music and Sound: An Integrative Transdisciplinary Synthesis

![Status](https://img.shields.io/badge/Status-Research_Manuscript_%26_Interactive_SPA-brightgreen)
![Author](https://img.shields.io/badge/Author-SAMUELSON_G-blue)
![Tech](https://img.shields.io/badge/Web_Stack-HTML5_%7C_Tailwind_CSS_%7C_Chart.js-amber)
[![DOI](https://img.shields.io/badge/DOI%20ResearchGate-10.13140/RG.2.2.35416.66564-blue)](https://doi.org/10.13140/RG.2.2.35416.66564)  
[![Zenodo](https://img.shields.io/badge/Zenodo-blue)](https://zenodo.org/records/19544116)  
[![Academia.edu](https://img.shields.io/badge/Academia.edu-blue)](https://www.academia.edu/165640547/Comprehensive_Analysis_of_Atmospheric_Pollution_Integrating_Fundamental_Chemistry_Epidemiological_Metrics_Sociological_Paradigms_and_Policy_Frameworks)  
![License](https://img.shields.io/badge/License-CC_BY_4.0_%2F_MIT-lightgrey)

**Author:** **SAMUELSON G**  
*Department of Systematic Musicology, Auditory Neuroscience, and Acoustic Engineering*

---

## Overview

This repository hosts the manuscript, empirical datasets, and interactive single-page web explorer for the research paper **"Acoustic Biophysics, Neurocognitive Architecture, and Generative Computation in Music and Sound: An Integrative Transdisciplinary Synthesis"** authored by **SAMUELSON G**.

While sound is a physical longitudinal pressure wave governed by continuum mechanics, music is an emergent, rule-based neurocognitive and sociocultural construct that exploits the biophysical constraints of the mammalian auditory pathway. This project unifies seven intersecting domains of music and sound science into both a formal academic paper and a browser-based interactive simulation suite.

---

## Repository Structure

| File / Directory | Description |
| :--- | :--- |
| `README.md` | Project documentation, theoretical overview, setup guide, conclusion, and citation details. |
| `index.html` | Self-contained Single-Page Application (SPA) featuring interactive biophysical calculators, psychoacoustic simulators, neurochemical visualizations, and a searchable 5-table empirical data explorer. |
| `paper.md` / `manuscript.pdf` | Full formal research paper including abstract, mathematical derivations, 5 empirical tables, figures, declarations, and 30 peer-reviewed references. |

---

## Core Scientific Domains Covered

1. **Epistemological & Evolutionary Foundations:** Cross-cultural behavioral invariants from the *Natural History of Song* corpus (infant care, healing, mourning, religiosity, formality, warfare) alongside archaeoacoustic reconstructions of prehistoric ritual spaces (such as Chavín de Huántar and the Cholula pyramid).
2. **Physical Acoustics & Cochlear Biomechanics:** Free-field wave propagation (344 m/s), pinna spectral filtering, active outer/inner hair cell amplification, the Greenwood frequency-position function, and three-dimensional morphometric compression between the Organ of Corti (mean 33.13 mm) and Spiral Ganglion (mean 13.69 mm; ratio 0.41) past the 1,000 Hz (360 degree) inflection point $V$.
3. **Psychoacoustics & Sensory Dissonance:** Critical bandwidth filtering (ERB/Bark), Plomp-Levelt roughness curves, Sethares's spectral-scale coupling demonstrating how harmonic and inharmonic instrument timbres dictate consonant tuning intervals, and boundary acoustic regimes (infrasound and the ultrasonic hypersonic effect above 20 kHz).
4. **Neurocognitive Architecture & Reward:** Reconciliation of domain-specific syntactic storage with shared prefrontal integration (Brodmann Area 47; P600 event-related potential) under Patel's Shared Syntactic Integration Resource Hypothesis (SSIRH), paired with the anatomical dissociation of striatal dopamine between the anticipatory phase (right caudate nucleus) and consummatory euphoria/chills (right nucleus accumbens).
5. **Clinical Neuromusicology & Neurologic Music Therapy (NMT):** Evidence-based auditory-motor entrainment using Rhythmic Auditory Stimulation (RAS) and immersive Virtual Reality (VR) to recruit cerebello-thalamo-cortical pathways and bypass basal ganglia pathology in Parkinson's disease, alongside Rhythmic Reading Training (RRT) for post-stroke aphasia.
6. **Computational Phonogram Archiving & Generative Audio AI:** Symbolic tokenization (REMI+) and continuous waveform compression via Neural Audio Codecs (EnCodec, SoundStream, DAC, MuCodec, FlowMAC), comparing Residual Vector Quantization (RVQ), Single Vector Quantization (SVQ), Group Vector Quantization (GVQ), and Finite Scalar Quantization (FSQ), as well as autoregressive codebook delay patterns in MusicGen and Loops Transformer.

---

## Interactive Web Application Features (`index.html`)

The accompanying web application translates the mathematical and empirical models of the research paper into interactive browser modules:

* **Greenwood & Spiral Ganglion Compression Simulator:** Real-time calculation of characteristic tonotopic frequencies along the Organ of Corti and Spiral Ganglion using custom sliders for Cochlear Duct Length (29.5 mm to 36.8 mm) and fractional distance from the apex:
  $$f(x) = A \left(10^{a x} - K\right)$$
* **Sethares Spectral-Scale Coupling Engine:** Live Chart.js simulation of sensory dissonance curves $D_F(\alpha)$ across pitch interval ratios $\alpha \in [1.0, 2.0]$, allowing instant toggling between harmonic spectra (strings/flute) and stretched inharmonic spectra (metallophones).
* **Temporal Striatal Dopamine Viewer:** Dual-modality timeline plotting normalized fMRI BOLD signal and $[^{11}\text{C}]\text{raclopride}$ PET dopamine displacement across the 15-second anticipatory epoch (Right Caudate) and peak consummatory chill epoch (Right Nucleus Accumbens).
* **Neural Audio Codec Trade-off Radar:** Multi-axis architectural comparison of RVQ, FSQ, and SVQ across waveform fidelity, channel perturbation robustness, language model simplicity, and subspace representational capacity.
* **Unified Empirical Data Explorer:** Interactive tab switching and real-time keyword filtering across all five empirical tables from the research paper:
  * **Table 1:** Three-Dimensional Morphometric Measurements of the Organ of Corti (OC), Spiral Ganglion (SG), and Middle Wall (MW) Across Nine Human Temporal Bone Specimens.
  * **Table 2:** Characteristic Tonotopic Frequencies and Inter-Subject Ranges Along the Organ of Corti (OC) and Spiral Ganglion (SG) by Angle of Rotation from the Round Window.
  * **Table 3:** Anatomical and Temporal Dissociation of Striatal Dopamine Release During Anticipatory and Consummatory Phases of Musical Reward.
  * **Table 4:** Clinical Neuromusicology and Acoustic Intervention Modalities, Target Pathologies, Neurobiological Mechanisms, and Functional Outcomes.
  * **Table 5:** Mathematical Taxonomy of Vector Quantization Paradigms in Neural Audio Codecs and Self-Supervised Audio Architectures.

---

## Conclusion

A rigorous transdisciplinary synthesis of music and sound reveals a profound structural isomorphism across physical, neurobiological, clinical, and computational scales:

1. **Biophysical and Computational Compression Isomorphism:** At the peripheral transduction stage, the human cochlea logarithmically maps a 1,000-fold acoustic frequency spectrum onto a 33.13 mm basilar membrane via the Greenwood function and compresses the apical 40% of low-frequency nerve fibers (frequencies at or below 1,000 Hz) into the final 19% of a 13.69 mm spiral ganglion. In an analogous mathematical manner, modern neural audio codecs compress continuous high-rate waveforms into hierarchical residual vector spaces where coarse fundamental structures precede fine spectral residuals.
2. **Psychoacoustic and Clinical Coupling:** Plomp-Levelt and Sethares sensory dissonance models demonstrate that musical harmony and scale structures are dynamically governed by cochlear critical bandwidths and instrumental spectral timbre rather than static numerological ratios. Consequently, restoring natural pitch perception and vocal formant resolution in cochlear implant recipients requires long lateral-wall electrode arrays (28 mm to 34 mm) and Anatomy-Based Fitting (ABF) strategies that account for the 1,000 Hz (360 degree) radial-to-tangential spiral ganglion inflection point $V$.
3. **Predictive Neurocognition and Therapeutic Entrainment:** Music functions as a transformative neurocognitive technology. The inferior frontal cortex (Brodmann Area 47) continuously evaluates structural expectations over unfolding acoustic sequences (indexed electrophysiologically by the P600 component under the Shared Syntactic Integration Resource Hypothesis), driving anticipatory dopamine release in the dorsal striatum (right caudate nucleus) and consummatory reward prediction signals in the ventral striatum (right nucleus accumbens). Simultaneously, rhythmic auditory pulses entrain cerebello-thalamo-cortical networks to bypass basal ganglia pathology, providing a robust neurobiological mechanism for clinical rehabilitation in Parkinson's disease, stroke, and aphasia.

---

## Declarations

* **Author Identification & Contributions:** **SAMUELSON G** conceived the transdisciplinary theoretical framework, performed the mathematical and morphometric synthesis across physical acoustics, cochlear neurobiology, psychoacoustics, clinical neuromusicology, and generative audio artificial intelligence, designed the interactive web simulations and structural tables, and wrote the manuscript.
* **Competing Interests:** The author (**SAMUELSON G**) declares no competing financial, commercial, or non-financial interests.
* **Funding Declaration:** This research received no specific grant from any commercial, public, or not-for-profit funding agency.

---

## Citation

If you use this research paper, empirical synthesis, or interactive simulation code in your academic work, please cite:

```bibtex
@article{samuelson2026music,
  author  = {Samuelson, G.},
  title   = {Acoustic Biophysics, Neurocognitive Architecture, and Generative Computation in Music and Sound: An Integrative Transdisciplinary Synthesis},
  journal = {Department of Systematic Musicology, Auditory Neuroscience, and Acoustic Engineering},
  year    = {2026},
  note    = {Includes interactive web simulation suite and empirical data explorer}
}
```

---

## License

* **Manuscript & Figures:** Licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
* **Interactive Web Application Code (`index.html`):** Licensed under the [MIT License](https://opensource.org/licenses/MIT).
