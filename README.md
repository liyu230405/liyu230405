<div align="center">

# Hi, I'm Liangpu Zhou

**Materials Science × Statistics × Machine Learning**<br>
**CCHO Final Bronze Medalist**

Undergraduate at the University of Science and Technology Beijing (USTB), working toward reliable and method-oriented AI for Science.

[![GitHub](https://img.shields.io/badge/GitHub-liyu230405-181717?logo=github)](https://github.com/liyu230405)
[![Email](https://img.shields.io/badge/Email-liyu230405%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:liyu230405@gmail.com)

</div>

## About me

- Materials Science and Engineering undergraduate (Materials Chemistry track) at **USTB**
- Pursuing a second degree in **Statistics**
- Interested in **reliable generative models**, **representation learning**, and **verifiable scientific agents**
- Bronze medalist in the **37th Chinese Chemistry Olympiad (Final)**
- Previously worked on chemistry-focused LLM data construction, quality control, and model evaluation at **Zhipu AI**
- Looking for research collaborations at the intersection of machine learning and materials discovery

## Education

**University of Science and Technology Beijing (USTB)** · Beijing, China<br>
B.Eng. candidate in Materials Science and Engineering, Materials Chemistry track · Sep 2024 - Jun 2028 (expected)<br>
Second degree in Statistics (in progress)

Selected coursework: Probability, Mathematical Statistics, Multivariate Statistical Analysis, Statistical Modeling and Computing, Statistical Learning, Machine Learning, and Operations Research.

## Research interests

- Generative modeling for periodic crystal structures
- Out-of-distribution generalization and evaluation in scientific ML
- Physics- and uncertainty-aware candidate screening
- Graph and self-supervised representation learning for materials
- Scientific agents with verifiable planning, tool use, and failure diagnosis

## Featured research

### [CDVAE Crystal Generation Benchmark & DFT Pre-screening](https://github.com/liyu230405/cdvae-crystal-screening)

A reproducible workflow for deciding which generated crystal structures are worth sending to expensive DFT validation.

- Evaluated **2,442 generated CIF structures** across Perov-5, Carbon-24, and MP-20
- Compared **13 training checkpoints** using parseability, geometry, chemistry, Valid/Unique/Novel/VUN, and distribution-fit metrics
- Added hard filters and **CHGNet** energy/force proxies before DFT
- Found that high validity does not necessarily imply useful diversity or novelty, and that longer training does not guarantee better generation
- Best Perov-5 5k result: **99.22% Valid** and **87.50% Strict VUN**

`Python` `PyTorch` `pymatgen` `SMACT` `CHGNet` `Crystal Generation`

## Selected engineering projects

### [MiniTag](https://github.com/liyu230405/minitag)

A DIY BLE proximity finder with a SwiftUI iOS app and Seeed XIAO nRF52840 firmware. It supports scanning, automatic connection, RSSI-based proximity feedback, buzzer control, and battery reporting.

`SwiftUI` `CoreBluetooth` `BLE` `nRF52840`

### [Pingdou Pattern Studio](https://github.com/liyu230405/pingdou-pattern-studio)

A browser-based pattern generator that converts images into numbered bead grids with color quantization, material counts, and high-resolution PNG export. Image processing stays local in the browser.

`TypeScript` `React` `Image Processing` `GitHub Pages`

## Honors

- **Bronze Medal (Third Prize)**, 37th Chinese Chemistry Olympiad - Final (第37届中国化学奥林匹克决赛), Nov 2023
- **Third Prize**, "Qingchuang Beijing" Challenge Cup Special Track for New Quality Productive Forces, May 2026<br>
  *DraftMind: Multimodal Intelligent Analysis Platform for Industrial Drawings*
- **Third Prize**, 1st USTB "Big Data Cup" Materials Intelligence Innovation Competition, Jun 2026<br>
  *Generative-AI-assisted Crystal Generation and Property Prediction Platform*

## Current questions

I am especially interested in research questions such as:

1. How should we evaluate crystal generators when validity alone overestimates scientific value?
2. How can periodic representations generalize across compositions, space groups, and datasets?
3. How can uncertainty, physical priors, and adaptive computation be combined in a closed-loop discovery system?
4. How can scientific agents make tool-using trajectories traceable, falsifiable, and recoverable after failure?

## Tools

`Python` · `PyTorch` · `Pandas` · `SQL` · `Git` · `LaTeX` · `pymatgen` · `SMACT` · `CHGNet`

## Contact

- Email: [liyu230405@gmail.com](mailto:liyu230405@gmail.com)
- GitHub: [@liyu230405](https://github.com/liyu230405)

> I am open to undergraduate research opportunities and collaborations in AI for Science, materials representation learning, and reliable scientific machine learning.
