[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23449728.svg)](https://doi.org/10.5281/zenodo.23449728)

# The Golden Ratio in Human Alphabets

**A Deterministic Rule on Letter Names Generates Exact Algebraic Constants**

This repository is the official landing page for the EOA (Engineering of Alphabets) research project. 

When a strict, deterministic substitution rule is applied to the written names of letters across 36 different human scripts, exact algebraic constants emerge as the dominant growth rates (Perron eigenvalues). Most strikingly, the square of the Golden Ratio (**φ² ≈ 2.618**) appears across multiple independent lineages, including Hebrew, Phoenician, Ge'ez, Thai, and Japanese-pronounced Latin. 

## 📄 The Research Paper

The full 11-page scientific paper, detailing the methodology, the 36 scripts, the statistical baselines, and the "Large Core" phenomena, is published on Zenodo:

👉 **https://doi.org/10.5281/zenodo.23449728**

## 📊 The Dataset & Verification

To ensure full scientific reproducibility while protecting the proprietary transliteration operator, the complete incidence matrices for all 36 scripts are provided as open data. 

👉 **https://doi.org/10.5281/zenodo.23440579**

### What is in the dataset ZIP file?
*   **36 CSV files:** The raw numeric incidence matrices for each script.
*   **`verify.py`:** A Python script to independently calculate the Perron eigenvalues and verify the constants.
*   **`README.txt`:** Dataset instructions.

## 🏆 Key Findings

*   **The Golden Ratio (φ²):** Emerges in the Semitic, Brahmic, and Japonic lineages.
*   **The Silver Ratio (1+√2):** Emerges in Arabic and Osmanya (Cushitic).
*   **The 2+√2 Constant:** Emerges in Aramaic, Syriac, and Burmese.
*   **The Predictive Law:** Scripts with rich, repeated letter names (Ogham, Glagolitic, Coptic) form large cores and yield high-degree algebraic constants. Scripts with short or self-referential names (Latin, Vietnamese, Tamil) collapse to 1.0.
*   **Reverse Engineering:** We successfully engineered a synthetic 2-letter alphabet to yield exactly **√3**, proving the mathematical mechanism is fully understood.

## 🔒 Note on the Operator
The specific internal transliteration operator used to map raw letter names to the incidence matrices is withheld under a staged disclosure agreement. The mathematical results rely solely on the provided matrices and can be fully verified using the open data. 

## 📬 Contact & Collaboration
We are actively seeking collaborators in graph theory, linguistics, and AI to explain the underlying mechanics of this structural phenomenon. 

**Bahaa BuDargham**
Independent Researcher, Montreal
ORCID: 0009-0005-2955-3703
