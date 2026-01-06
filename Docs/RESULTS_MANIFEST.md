# Results Manifest

This document maps each figure included in the repository to the
corresponding figure in the paper *“Fusion Matters: Length-Aware Analysis of
Positional-Encoding Fusion in Transformers”*.

The figures included here **exactly match the figures shown in the paper**.

Some figures underwent **label-only renaming** (e.g., `gate` → `gate-Scalar`,`MLP` → `MLP-GATE`)
to ensure terminological consistency between the experiments and the final
paper.  
No data, curves, numerical values, or visual encodings were altered.

---

## Figure 1a — Additive Fusion
**File:** `fig1_a_Additive.png`  
**Paper:** Figure 1a  
**Description:** Illustration of standard element-wise additive fusion of
token embeddings and positional encodings.

---

## Figure 1b — Concat + Projection Fusion
**File:** `fig1_b_concat_projection.png`  
**Paper:** Figure 1b  
**Description:** Concatenation of token and positional embeddings followed by
linear projection to the model dimension.

---

## Figure 2 — Gate-CNN Fusion
**File:** `fig2_gate_cnn.png`  
**Paper:** Figure 2  
**Description:** Local convolutional positional gating mechanism operating
solely on positional encodings.

---

## Figure 3 — ArXiv Paired-Seed Deltas (Gate / Concat vs Add)
**File:** `fig3_arxiv_paired_deltas_gateScalar_concat.png`  
**Paper:** Figure 3  
**Description:** Paired per-seed accuracy deltas (Gate-Scalar − Add) on the ArXiv dataset, computed under identical random seeds.

---

## Figure 4a — ArXiv Accuracy by Fusion
**File:** `fig4_a_arxiv_accuracy.png`  
**Paper:** Figure 4a  
**Description:** Mean test accuracy across fusion mechanisms on the ArXiv
dataset.

---

## Figure 4b — ArXiv Inference Latency by Fusion
**File:** `fig4_b_arxiv_latency.png`  
**Paper:** Figure 4b  
**Description:** Relative inference latency comparison across fusion
mechanisms on ArXiv.

---

## Figure 5 — ArXiv Paired-Seed Deltas (Gate-Scalar vs Gate-CNN)
**File:** `fig5_arxiv_paired_deltas_gate_scalar_gateCNN.png`  
**Paper:** Figure 5  
**Description:** Paired per-seed accuracy deltas on the ArXiv dataset comparing
Gate-Scalar and Gate-CNN relative to Add.

---

## Figure 6 — AG News Paired-Seed Deltas
**File:** `fig6_paired_deltas_agnews.png`  
**Paper:** Figure 6  
**Description:** Paired per-seed accuracy deltas on the AG News dataset,
illustrating limited and inconsistent fusion effects on short sequences.

---

## Figure 7 — IMDB Paired-Seed Deltas
**File:** `fig7_paired_deltas_imdb.png`  
**Paper:** Figure 7  
**Description:** Paired per-seed accuracy deltas on the IMDB dataset,
showing modest and less consistent fusion effects on medium-length documents.
