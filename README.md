# Thesis Proposal

This repository contains the LaTeX source of a working draft of the thesis proposal. The draft has three parts.

1. Operational background. Two observations, B1 and B2, follow the background. B1 concerns a loss of airspace or facility availability after aircraft have departed. B2 concerns the use of the same network design for normal service and for disruption response.
2. A review of related studies in seven areas. Each area ends with an observation, and the observations are numbered 1 to 7.
   - Operating context and traffic-management frameworks
   - Airspace geometry, aircraft performance, and energy
   - Traffic planning and coordination
   - Disruption response and contingency management
   - Network configuration and resilience
   - Performance evaluation, uncertainty, and verification
   - Disruption recovery and joint design in related transportation systems
3. Research formulation. This part states the study context and a provisional research gap, then gives the Research Objective and three Research Questions with a description of the work under each question. Research Question 2 concerns how emergency procedures and corridor designs are evaluated. Research Question 3 also considers the efficiency of normal operations.

## Opening the project in Overleaf

Import this repository into Overleaf, or download it from GitHub as a ZIP file and upload it as a new Overleaf project.

- Main document: `main.tex`
- Compiler: XeLaTeX
- References: 24 entries in American Institute of Aeronautics and Astronautics (AIAA) format, written directly in `main.tex`

The project does not need a separate bibliography file or a custom document class. Citations use LaTeX citation keys, and the references are numbered in order of first appearance.

The document is a working draft. It is not a complete thesis proposal and does not use a university thesis template.

## Automatic compilation

When `main.tex` changes on the `main` branch, GitHub Actions compiles the document with Tectonic, a XeTeX-based engine. The compiled PDF is saved as the workflow artifact `literature-and-observations-pdf`.
