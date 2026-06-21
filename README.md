# Lumerical-FDTD-Simulation-Based-Research
This repository is a curated collection of resources for learning and practicing Finite-Difference Time-Domain (FDTD) simulation in Ansys/Lumerical, built around a nano-photonics case study. It includes original educational material, a hands-on simulation skill test, and a selection of academic papers to support learning and simulation benchmarking.

📂 Repository Contents

🌟 Original Work
`Introduction to FDTD.pptx` — Mastering Lumerical FDTD: From Theory to Simulation, by Ehatasham Haque.
This presentation provides a foundational overview of FDTD theory (Yee grid, time marching, numerical stability) and walks through a practical simulation workflow in Lumerical FDTD (geometry definition, source injection, monitor setup, boundary conditions, and result analysis), closing with a pre-run checklist.

🧪 Simulation Skill Test
`Sim Skill Test.pdf` — An excerpt of the Supplementary Information from:
> Kharintsev, S. S., Noskov, A. I., Battalova, E. I., Katrivas, L., Kotlyar, A. B., Merham, J. G., Potma, E. O., Apkarian, V. A., \& Fishman, D. A. (2024). Photon Momentum Enabled Light Absorption in Silicon. \*ACS Nano\*, \*18\*(39), 26532–26540. https://doi.org/10.1021/acsnano.4c02656
This document is used as a hands-on simulation exercise: students are asked to reproduce the FDTD/FEM field-distribution simulation in Figure SF4 (through panel b), a Si tip apex over a 2 nm gold bump under focused continuous-wave illumination, in Lumerical FDTD, before comparing their result against the published field profile.
> 
📚 Collected Research Papers (Third-Party)
Published papers included for reference and simulation benchmarking, alongside the presentation and skill test above.

File	Citation:

`01\_2023\_Komisar.pdf`<br>`01\_2023\_Komisar\_supplement.pdf`	Komisar, D., Kumar, S., Kan, Y., Meng, C., Kulikova, L. F., Davydov, V. A., Agafonov, V. N., & Bozhevolnyi, S. I. (2023). Multiple Channelling Single-Photon Emission with Scattering Holography Designed Metasurfaces. Nature Communications, 14, 6253. https://doi.org/10.1038/s41467-023-42046-3

`02\_2026\_Farmani.pdf`	Farmani, A., & Omidniaee, A. (2026). FDTD-Based Design of High Quality Factor Quantum Dot Photonic Crystal Nanolaser for Next-Generation Nanotechnologies. Scientific Reports, 16, 6985. https://doi.org/10.1038/s41598-026-36019-x

`03\_2024\_Yang.pdf`<br>`03\_2024\_Yang\_supplement.pdf`	Yang, J., Chen, Y., Rao, Z., Zheng, Z., Song, C., Chen, Y., Xiong, K., Chen, P., Zhang, C., Wu, W., Yu, Y., & Yu, S. (2024). Tunable Quantum Dots in Monolithic Fabry-Perot Microcavities for High-Performance Single-Photon Sources. Light: Science & Applications, 13, 33. https://doi.org/10.1038/s41377-024-01384-7

🛠 Simulation Focus
The materials here center on practical use of the Ansys/Lumerical FDTD solver, including:
Yee grid discretization and time-marching field updates
Mesh design (override regions, fine meshing near nanoscale features)
Source selection (Gaussian pulses, plane waves, point/mode sources)
Boundary conditions: Perfectly Matched Layers (PML), periodic, PEC/PMC
Time- and frequency-domain monitors, far-field/near-field analysis
Coupled FDTD–FEM workflows for optical absorption and heat generation

⚖️ Copyright & Attribution
Presentation: Created by Ehatasham Haque. Licensed under the MIT License included in this repo.
Sim Skill Test PDF & Research Papers: These documents are the property of their respective authors and publishers (ACS Nano, Nature Communications, Scientific Reports, Light: Science & Applications). They are included here for non-commercial educational and research purposes only.
