# Fusion Matters: Length-Aware Analysis of Positional-Encoding Fusion in Transformers

This repository accompanies the paper **“Fusion Matters: Length-Aware Analysis of Positional-Encoding Fusion in Transformers.”**

It provides:
- the paper figures,
- cleaned reproducibility-oriented notebooks,
- and documentation mapping figures to the paper.

The goal of this repository is **transparency and clarity**, not raw experiment archival.

---

## Repository Structure
notebooks/ Reproducibility-oriented notebooks

paper/ Paper PDF


results/figures/ Final figures used in the paper

docs/ Documentation (results manifest, notes)


---

## Notebooks

The notebooks in `notebooks/` are **clean reproduction notebooks**.

They are designed to:
- reflect the experimental setups described in the paper,
- be readable and self-contained,
- regenerate results conceptually equivalent to those reported.

They may differ from the original experiment notebooks in structure and presentation, but **not in experimental intent**.

---

## Results and Figures

Only the **final figures used in the paper** are included in this repository.

Some figures underwent **label-only renaming** ( `gate` → `gate-Scalar`, `MLP` → `MLP-Gate`) to ensure terminological consistency between experiments and the final paper.  
No data, numerical values, or visual encodings were altered.

A detailed mapping between figures and the paper is provided in: [Results Manifest](docs/RESULTS_MANIFEST.md)


---

## Datasets

Datasets used in the experiments are **not included** in this repository.

Please refer to the paper for dataset descriptions and sources.

---

## License

This repository is provided for academic and research purposes.

