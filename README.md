[![.github/workflows/latex.yml](https://github.com/mohamedayas16/CS_Fase1_Assingment/actions/workflows/latex.yml/badge.svg)](https://github.com/mohamedayas16/CS_Fase1_Assingment/actions/workflows/latex.yml)

# Semester II - Computational Science Project

This project contains computational analysis scripts and documentation for the course assignments which include the actual datas and reports in lab at FCFM, UANL.

## Repository Structure

```text
├── Data/          # Input datasets and generated data
├── Notebook/      # Plans and records of the project
├── docs/          # Reports, TeX documentation, and notes
│   └── report.tex # Main assignment report
├── src/           # Source code and computational scripts
│   └── analysis.py# Core analysis script
├── .gitignore     # Git ignore rules
├── README.md      # Project overview and reproduction instructions
└── LICENSE        # GNU GPL V3 LICENSE of the project.
```

## Getting Started & Reproduction Instructions

Follow these steps to reproduce the environment and run the analysis on a clean machine:

### 1. Prerequisites
Ensure you have **Python 3.8+** installed. The project relies on the following core numerical and visualization libraries:
* Required packages:
  ```bash
  pip install numpy matplotlib scipy
  ```
### 2. Clone the repository
First, grab a local copy of the repository and switch into the project directory:
  ```bash
  git clone https://github.com/mohamedayas16/CS_week2_assingment.git
  cd CS_week2_assingment
  ```
### 3. Run the computational analysis script
To process the data and generate the computational results and figures, run the main analysis script:
```bash
python src/analysis.py
```
### 4. Compile the report
If you want to re-generate the assignment PDF report from the LaTeX source:
```bash
pdflatex docs/report.tex
```
## HOW to Cite
If you use any part of this repository or want to reference this analysis, please cite it like this:
```bibtex
@misc{computational_science_2026,
  author = {Mohamed Ayas Mohamed Kasim},
  title = {Semester II - Computational Science Project Repository},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/mohamedayas16/CS_week2_assingment}}
}
```
## License

This project is licensed under the **GNU General Public License v3.0 (GPLv3)**. See the [LICENSE](LICENSE) file for the full text.

### Why GPLv3?

This repository contains research code and analytical tools developed as part of my thesis. The GPLv3 was chosen to support **open science and scientific reproducibility**:

* **Guaranteed Open Access:** Anyone is free to use, modify, and distribute this codebase, provided that any derivative works or distributed modifications remain licensed under the GPLv3.
* **Community Contribution:** This prevents scientific tooling developed through public/institutional research from being absorbed into closed-source proprietary systems without returning improvements to the research community.
* **Patent Protection:** GPLv3 includes an explicit grant of patent rights from contributors to users, protecting downstream researchers from unexpected patent litigation.
