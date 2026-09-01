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
└── LICENSE        # MIT LICENSE of the project.
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
This is the change that needs to be done in the readme file.
## Repository Structure

```text
├── data/
│   ├── raw/
│   │   ├── cv/            # Raw Cyclic Voltammetry scans (.cor)
│   │   ├── eis/           # Raw Electrochemical Impedance data (.cor / .dta)
│   │   └── mott_schottky/ # Raw Mott-Schottky capacitance scans (.cor)
│   └── processed/         # Parsed CSVs and fitted parameters (e.g., flat-band potential)
├── scripts/               # Python/MATLAB scripts for data extraction and plotting
├── figures/               # Generated publication-quality figures (.pdf / .png)
├── chapters/              # LaTeX source files for thesis chapters
├── .gitignore             # Ignored temporary files, caches, and LaTeX logs
├── LICENSE.md             # Dual license terms (CC BY 4.0 for prose, MIT for code)
└── README.md              # Project overview and reproduction instructions
```
