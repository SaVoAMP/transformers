# Transformer Project

This repository contains two main components:

### 📄 `latex/`
This folder includes a written report (`TransformerSaVo.pdf`) on Transformer architectures, along with the full LaTeX source files. The report is written in German and provides a theoretical foundation for understanding the key components and structure of Transformers.

### 📓 `notebooks/`
This folder contains a set of interactive Jupyter notebooks designed to help visualize and experiment with core building blocks of Transformer architectures. Topics include:

- Token embeddings
- Positional encodings
- Multi-head self-attention

Each notebook contains code, explanations, and simple visualization tools. You are encouraged to modify input parameters and explore how the model components behave.

---

## Setup Instructions

1. Create and activate a virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   
## Notes
- The report can be compiled using `pdflatex` and `biber` (for bibliography).
- Image rendering in notebooks assumes you run them from the `notebooks/` directory. If needed, adjust paths or use `os.path.abspath()` for portability.
- The installation process was tested with Python 3.9 on Linux Mint 21.3.
