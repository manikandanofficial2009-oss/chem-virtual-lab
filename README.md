# 🧪 Cheminformatics Virtual Laboratory

## Aim

To develop a foundational understanding of Cheminformatics by using
computational tools to represent, visualize and analyze chemical structures.

## Learning Objectives

Students will be able to

- Convert molecular representations using SMILES and InChI.
- Visualize molecular structures in 2D and 3D.
- Calculate molecular descriptors.
- Understand structure–property relationships.
- Evaluate drug-likeness and compare molecules by similarity.

## Features

- SMILES validation, 2D and interactive 3D visualization
- Molecular descriptors: Molecular Weight, LogP, TPSA, H-bond donors/acceptors,
  rotatable bonds, ring count, σ/π bond counts and more
- Structure–property comparison of multiple molecules (CSV download)
- **Drug-Likeness:** Lipinski Rule of Five, Veber rules, QED score, PAINS screening
- **Functional Groups & Substructure:** functional group finder with highlighted
  atoms, and substructure search over a molecule library
- **Similarity & Fingerprints:** Morgan fingerprints, Tanimoto similarity matrix
  and heatmap, library ranking against a query molecule
- **Format Converter & Identifiers:** SMILES ⇄ InChI, InChIKey, Murcko scaffold,
  stereocentres, elemental composition, MOL/SMILES downloads
- Assessment quiz and a combined PDF report generator

## Installation

Install the required packages

```bash
pip install -r requirements.txt
```

Run the app

```bash
streamlit run app.py
```

## Developed by

Mani Kandan S, Cyber A
SRM Institute of Science and Technology, Tiruchirappalli
