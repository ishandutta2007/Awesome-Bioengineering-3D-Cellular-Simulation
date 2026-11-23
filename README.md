# Awesome-Bioengineering-3D-Cellular-Simulation
# Awesome-Bioengineering-3D-Cellular-Simulation

<FollowUp>
Would you like to **add a dedicated section for open-source SBML/CellML biological model repositories & spatial transcriptomics tools** (like `BioModels`, `Squidpy`, `Scanpy`) or **generate the next `README.md` repository**?
</FollowUp>
# Awesome-Bioengineering-3D-Cellular-Simulation

# Awesome Bioengineering & 3D Cellular Simulation 🌟

> **Top Bioengineering 3D Cellular Simulation (Opensource)**  
> A curated list of the best bioengineering, systems biology, and 3D cellular / multicellular simulation tools — with a strong focus on **open-source** and self-hostable alternatives.  
> 🌟 **Star if you like it!** 🌟

Bioengineering and 3D cellular simulation tools enable modeling of molecular interactions, biochemical networks, cell mechanics, tissue morphogenesis, and multicellular systems. Commercial platforms such as Schrödinger Maestro, SimBiology, and various cloud offerings provide polished environments, while a rich open-source ecosystem offers agent-based frameworks, molecular dynamics engines, visualization suites, and spatial multicellular simulators that researchers can fully control and extend.

This list prioritizes **open-source GitHub projects and freely available academic tools** while keeping SaaS/hosted platforms clearly separated.

## Table of Contents

- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS / Hosted Platforms

These are popular commercial or hosted bioengineering, molecular modeling, and cellular simulation platforms (closed-source / hosted or commercial licenses):

- **[Schrödinger Maestro](https://www.schrodinger.com/)** — Comprehensive molecular modeling and simulation suite with advanced visualization, docking, and dynamics capabilities.
- **[SimBiology](https://www.mathworks.com/products/simbiology.html)** (MathWorks) — MATLAB-based environment for modeling, simulating, and analyzing biological systems and pharmacokinetic/pharmacodynamic models.
- **[GROMACS Cloud / commercial cloud offerings](https://www.gromacs.org/)** — Hosted or cloud-accelerated versions of molecular dynamics workflows (while core GROMACS is open-source).
- **[CellDesigner](https://www.celldesigner.org/)** — Process diagram editor for gene-regulatory and biochemical networks (widely used; commercial support options available).
- **[BioUML](https://www.biouml.org/)** — Integrated platform for systems biology with modeling, simulation, and analysis features (has commercial/enterprise aspects).
- **[NetLogo Bio / related hosted models](https://ccl.northwestern.edu/netlogo/)** — Agent-based modeling environment frequently used for biological systems (core is free; some hosted/educational deployments exist).
- **Rosetta Commons commercial / hosted services** — Advanced protein structure prediction and design platform with commercial licensing options alongside academic access.
- **ChimeraX commercial use** — Molecular visualization and analysis (free for academic/government; commercial licenses available).

## Open-Source GitHub Projects

Open-source alternatives and tools you can self-host, run locally, or extend. These cover molecular dynamics, biochemical network simulation, agent-based multicellular modeling, 3D cell mechanics, and visualization.

### Multicellular & Agent-Based 3D Simulation

- **[PhysiCell](https://github.com/MathCancer/PhysiCell)** (and PhysiCell Studio)  
  Leading open-source agent-based framework for large-scale 2D/3D multicellular systems biology. Simulates cell movement, growth, division, interaction, and death with diffusing substrates. Scalable to tens or hundreds of thousands of cells on desktop hardware. BSD-licensed, actively maintained, with browser-based modeling options.

- **[CompuCell3D/CompuCell3D](https://github.com/CompuCell3D/CompuCell3D)**  
  Multiscale multicellular virtual tissue modeling and simulation environment. Supports Python scripting, GUI, and complex cellular automata / Potts-model style simulations of tissues and morphogenesis. MIT license.

- **[megasonlab/goo](https://github.com/megasonlab/goo)**  
  Blender-based library for physics-driven modeling of biological cells, tissues, and embryos. Surface-mesh cells with growth, division, adhesion, and signaling. Excellent for realistic 3D visualization and interactive exploration.

- **[jdisset/MecaCell](https://github.com/jdisset/MecaCell)**  
  Lightweight, efficient open-source cellular physics engine focused on morphogenetic engineering and agent-based simulations. Core library + optional OpenGL viewer.

- **[SoftSimu/CellSim3D](https://github.com/SoftSimu/CellSim3D)**  
  GPU-accelerated 3D cell simulator for mechanistic aspects of cell growth and division (CUDA/C++).

### Biochemical Network & Systems Biology Simulation

- **[copasi/COPASI](https://github.com/copasi/COPASI)**  
  Widely used open-source application for simulation and analysis of biochemical networks. Supports deterministic and stochastic simulation, parameter estimation, metabolic control analysis, and SBML. Artistic License.

- **[virtualcell/vcell](https://github.com/virtualcell/vcell)** (Virtual Cell / VCell)  
  Comprehensive open-source framework for modeling and simulating cell biology from pathways to biophysics. Supports spatial and non-spatial, deterministic and stochastic simulations, reaction networks, and rule-based modeling. MIT license.

- **Tellurium, PySCeS, libRoadRunner, and related SBML toolkits** — Python-centric environments and high-performance libraries for systems biology model simulation and analysis.

### Molecular Dynamics, Structure & Visualization

- **[GROMACS](https://github.com/gromacs/gromacs)**  
  High-performance open-source molecular dynamics package primarily for proteins, lipids, and nucleic acids. Extremely widely used in bioengineering and computational biology. LGPL.

- **[RBVI/ChimeraX](https://github.com/RBVI/ChimeraX)** (UCSF ChimeraX)  
  Next-generation molecular visualization and analysis platform (successor to UCSF Chimera). Source available; free for academic and government use. Excellent for 3D structures, density maps, and sequences.

- **Rosetta Commons open components / academic distributions** — Protein structure prediction, design, and docking tools with significant open-source and freely available academic codebases.

- **Avogadro, PyMOL (open-source builds), Jmol, and related molecular viewers** — Complementary open tools for structure editing and visualization.

### Additional Notable Open-Source Projects

- **[huangserva/3DCellForge](https://github.com/huangserva/3DCellForge)**  
  AI-powered interactive 3D model generation, inspection, and presentation studio (React + Three.js). Supports image-to-3D workflows and GLB handling; useful for rapid 3D cellular / biological asset creation and visualization.

- CellModeller, PhysiBoSS (Boolean network extension of PhysiCell), MCell (particle-based spatial stochastic simulation), Cytosim (cytoskeletal filaments), and various phase-field / active-matter 3D cell models.

> **Tip**: For large-scale multicellular tissue simulations start with **PhysiCell** or **CompuCell3D**. For biochemical network dynamics use **COPASI** or **VCell**. For molecular-level work combine **GROMACS** with **ChimeraX**. Many of these tools interoperate via SBML, VTK, or standard file formats and can be scripted in Python.

## How to Contribute

Contributions are welcome and encouraged!

1. Fork the repository
2. Add a new tool under the appropriate section (keep SaaS and Open-Source strictly separate)
3. Use the same format: **Name** — short description + key features + license/link
4. Prefer actively maintained projects with clear documentation, reproducible examples, and preferably cross-platform support
5. Submit a Pull Request

Please keep descriptions neutral and factual. Open-source projects are the primary focus of this list.

## Disclaimer

This is a community-curated list for informational and educational purposes only.  
Inclusion does not constitute an endorsement. Always review licenses, citation requirements, computational resource needs, and validation status before using any tool for research or publication.

Some projects may have dual licensing, academic-only free tiers, or commercial cloud offerings. Check the actual LICENSE file and documentation. Simulation results should be carefully validated against experimental data.

---

**Made with ❤️ for the open-source bioengineering and computational biology community**  
If this list helped you, please ⭐ the repo!
