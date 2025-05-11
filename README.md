# Psychiatry and Papers

This repository contains research notebooks, data workflows, and manuscript drafts focused on topics in psychiatry, neuroscience, and computational mental health.

The project is designed to support:
- Exploratory and reproducible analysis using Jupyter Notebooks
- Integration with the [Neurodesk](https://www.neurodesk.org/) platform
- Ongoing literature reviews and paper drafts
- Structured data organization for collaboration and sharing

---

## Project Structure

```
psychiatry_and_papers/
├── notebooks/       # Jupyter notebooks for analysis and exploration
├── data/            # Raw and processed data (not tracked by Git)
│   ├── raw/
│   └── processed/
├── papers/          # Drafts, manuscripts, and citation files
├── scripts/         # Python or shell scripts for automation and analysis
├── envs/            # Conda environment files
├── .gitignore       # Files and folders excluded from Git
├── README.md        # You're here.
└── LICENSE          # (Optional) License for reuse
```

---

## 🛠 Getting Started

### 1. Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/psychiatry_and_papers.git
cd psychiatry_and_papers
```

### 2. Start a Jupyter environment (via Neurodesk or local tools)

This project is compatible with Neurodesk and can be mounted into the container:

```bash
docker run --rm -it -v $(pwd):/data vnmd/neurodesktop:latest
```

Inside Neurodesk, navigate to `/data` to access your files.

---

## Notebooks

Notebooks live in the `notebooks/` directory and cover topics such as:

- Exploratory data analysis
- Simulation-based modeling
- Cognitive and clinical assessments
- Manuscript figures and tables

---

## License

This project is open for academic and research collaboration. Please reach out before reuse. (Consider adding an official license like MIT or CC-BY.)
