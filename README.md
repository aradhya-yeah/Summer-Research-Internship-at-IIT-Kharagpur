# Characterization of the Interaction Between DDX3X and Influenza B Virus Genomic RNA (Presentation)

[![Presentation](https://img.shields.io/badge/Format-PowerPoint%20PPTX-B7472A.svg?logo=microsoft-powerpoint&logoColor=white)](final_report.pptx)
[![Research Area](https://img.shields.io/badge/Domain-Molecular%20Virology%20%26%20Biophysics-0A85EA.svg)](#)
[![Status](https://img.shields.io/badge/Status-Completed%20Research-success.svg)](#)

This repository contains the final research internship presentation, complete extracted high-resolution figures, detailed captions, and experimental documentation for the research project conducted by **Aradhya Gupta** under the supervision of **Prof. Arindam Mondal** at the **Molecular Virology Laboratory, Department of Bioscience and Biotechnology, Indian Institute of Technology (IIT) Kharagpur**.

---

## Research Overview

Influenza viruses (family *Orthomyxoviridae*) represent major threats to global public health, accounting for an estimated 3 to 5 million severe cases of respiratory illness annually. While Influenza A virus (IAV) is notorious for worldwide pandemics across human and animal reservoirs, **Influenza B virus (IBV)** circulates almost exclusively in humans, inflicting significant seasonal morbidity and mortality.

Viral transcription and genome replication depend fundamentally on the viral ribonucleoprotein complex (vRNP) interacting with host cellular factors. **Human DEAD-box RNA Helicase 3 X-linked (DDX3X)** is an ATP-dependent RNA helicase central to RNA metabolism, mRNA export, translation initiation, stress granule dynamics, and innate immune signaling (Type I Interferon induction).

### Key Scientific Objectives
1. **Recombinant DDX3X Expression & Purification**: Recombinantly express His-tagged DDX3X in *Escherichia coli* BL21(DE3) cells, optimize induction conditions, and purify using Ni-NTA immobilized metal affinity chromatography (IMAC) followed by Size Exclusion Chromatography (SEC).
2. **In Vitro Generation of Influenza B Viral RNA**: Clone and amplify mini viral gene segments of IBV (HA, PA, NS) and generate RNA transcripts via T7 in vitro transcription (IVT).
3. **Characterization of Protein–RNA Interactions**: Investigate the direct binding affinity and segment-specificity of DDX3X with Influenza B virus genomic RNA segments (PB1, PB2) using Electrophoretic Mobility Shift Assays (EMSA).

---

## Repository Structure

```text
├── final_report.pptx       # Master presentation slide deck (21 slides)
├── FIGURE_CAPTIONS.md      # Comprehensive catalog of figures with scientific captions
├── .gitignore              # Git ignore rules for office cache & temporary files
├── README.md               # Repository documentation and project overview
└── figures/                # Directory containing all 50+ extracted slide figures and media
    ├── image1.png          # Institutional emblems & slide visuals
    ├── image2.svg          # South Asian University vector crest
    ├── image3.png          # IIT Kharagpur crest
    ├── image4.png          # Influenza virion architecture diagram
    ├── image22.png         # DDX3X host factor conceptual banner
    ├── image23.png         # Crystal structure of DDX3X helicase core
    ├── image24.png         # Prior lab data: IBV promoter downregulation
    ├── image26.png         # SDS-PAGE: DDX3X IPTG induction check
    ├── image27.png         # SDS-PAGE: Ni-NTA elution fractions
    ├── image29.png         # SEC Coomassie gel / chromatogram profile
    ├── image30.png / .tif  # Agarose gel: PCR template amplification
    ├── image35.png / .tif  # Colony PCR verification of clones
    ├── image38.png         # In vitro transcription RNA product
    ├── image40.png         # Native PAGE autoradiogram of EMSA binding
    ├── image42.png / .tif  # EMSA titration binding curve: PB1 segment
    ├── image43.png / .tif  # EMSA titration binding curve: PB2 segment
    └── ...                 # Additional vector components and diagram assets
```

---

## Extracted Figures & Scientific Captions Summary

For the full detailed catalog, please refer to [FIGURE_CAPTIONS.md](FIGURE_CAPTIONS.md).

| Figure File | Slide | Category | Scientific Description |
|:---|:---:|:---|:---|
| `figures/image2.svg` | Slide 1 | Institution Logo | Official crest of **South Asian University (SAU)**, New Delhi. |
| `figures/image3.png` | Slide 1 | Institution Logo | Official crest of **IIT Kharagpur**, Department of Bioscience and Biotechnology. |
| `figures/image4.png` | Slide 3 | Schematic Diagram | **Architecture of the Influenza Virion**: Depicts lipid bilayer, surface glycoproteins (HA, NA, M2), matrix protein M1, and ribonucleoprotein complexes (vRNPs consisting of PB1, PB2, PA, and NP). |
| `figures/image23.png` | Slide 7 | Structural Biology | **3D Structure of DDX3X Helicase Core**: Ribbon diagram highlighting RecA-like domains 1 and 2, ATP-binding pocket, and RNA-binding cleft. |
| `figures/image24.png` | Slide 8 | Experimental Data | **DDX3X Downregulation of IBV**: Comparative reporter assay demonstrating that DDX3X selectively downregulates IBV RNA synthesis at the promoter level. |
| `figures/image26.png` | Slide 11 | SDS-PAGE Gel | **Expression Analysis of DDX3X**: Uninduced vs. IPTG-induced *E. coli* BL21(DE3) lysates demonstrating target protein overexpression at ~73 kDa. |
| `figures/image27.png` | Slide 11 | SDS-PAGE Gel | **Ni-NTA Affinity Chromatography**: Elution fractions (E1–E6) demonstrating high purity of His-tagged DDX3X. |
| `figures/image29.png` | Slide 12 | Chromatography | **Size Exclusion Chromatography (SEC)**: Monomeric fraction profile and SDS-PAGE purity confirmation. |
| `figures/image30.png` | Slide 14 | Agarose Gel | **PCR Amplification of Mini IVT Templates**: Gel electrophoresis verifying amplicons for IBV HA (84 bp), PA (138 bp), and NS (134 bp). |
| `figures/image35.png` | Slide 15 | Agarose Gel | **Colony PCR Verification**: Screening of transformants using CMV-F/BGH-R primers confirming successful cloning into plasmids. |
| `figures/image38.png` | Slide 16 | Urea-PAGE Gel | **In Vitro Transcription (IVT)**: T7 RNA polymerase synthesized viral RNA products resolved to confirm template integrity. |
| `figures/image42.png` | Slide 19 | EMSA Gel | **Electrophoretic Mobility Shift Assay (PB1)**: Native gel showing concentration-dependent binding of DDX3X (0 to 20 µM) to radiolabeled IBV PB1 segment. |
| `figures/image43.png` | Slide 19 | EMSA Gel | **Electrophoretic Mobility Shift Assay (PB2)**: Native gel showing concentration-dependent binding of DDX3X (0 to 20 µM) to radiolabeled IBV PB2 segment. |

---

## Experimental Workflow & Key Findings

1. **Recombinant Expression & Purification**:
   - DDX3X recombinant protein was expressed at high yields in *E. coli* BL21(DE3) with IPTG induction.
   - Ni-NTA affinity chromatography and size-exclusion chromatography delivered homogeneous, monomeric protein migrating at ~73 kDa without degradation.
2. **Template Preparation & In Vitro Transcription**:
   - Influenza B genomic mini-templates (HA, PA, NS) were successfully amplified and cloned into plasmid vectors.
   - T7 RNA polymerase catalyzed in vitro transcription, generating viral RNA segments for interaction assays.
3. **Gel Shift Binding Assays**:
   - Recombinant DDX3X displayed robust and concentration-dependent complex formation with radiolabeled IBV genomic RNA segments (PB1 and PB2), confirming direct physical interaction between the host RNA helicase and viral genomic RNA.

---

## Author & Acknowledgments

- **Investigator**: Aradhya Gupta (1st Year BS-MS, South Asian University)
- **Principal Investigator & Supervisor**: Prof. Arindam Mondal, Department of Bioscience and Biotechnology, Indian Institute of Technology (IIT) Kharagpur
- **Laboratory**: Molecular Virology Laboratory, IIT Kharagpur
- Special thanks to Mr. Soumik Dey and all members of the Molecular Virology Laboratory for technical guidance and collaborative discussions.
