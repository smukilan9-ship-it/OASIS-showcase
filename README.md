<!-- IHC Analyzer — public showcase repository. -->

<p align="center">
  <img src="images/hero.png" alt="IHC Analyzer — a trustworthy digital pathology platform" width="100%">
</p>

<h1 align="center">IHC Analyzer</h1>

<p align="center">
  <b>A digital-pathology platform for trustworthy spatial analysis of brightfield immunohistochemistry.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Digital%20Pathology-0d0d0d?style=flat-square">
  <img src="https://img.shields.io/badge/Spatial%20Analysis-0d0d0d?style=flat-square">
  <img src="https://img.shields.io/badge/Validation--Aware-16a34a?style=flat-square">
  <img src="https://img.shields.io/badge/Batch%20Processing-0d0d0d?style=flat-square">
</p>

<p align="center">
  <a href="https://ihc-analysis-interactivedemo.vercel.app"><b>▶&nbsp;&nbsp;Try the Interactive Demo</b></a>
</p>

<br>

---

## Experience it in two minutes

> **The best way to understand IHC Analyzer is to use it.**
>
> The **[Interactive Demo](https://ihc-analysis-interactivedemo.vercel.app)** walks you through the entire workflow — batch processing, segmentation, quantification, trustworthy spatial analysis, and same-section co-expression — on preloaded example data. No installation, no setup, no uploads.

<p align="center">
  <a href="https://ihc-analysis-interactivedemo.vercel.app"><b>→&nbsp;&nbsp;Launch the Interactive Demo</b></a>
</p>

---

## What it is

Reading *where* the immune system sits around a tumour — not just how many cells there are — has become one of the most important tools in cancer research. Today that usually means a six-figure multiplex imaging system, or a fragile stack of one-off scripts that is easy to fool.

**IHC Analyzer is a single, professional platform that does the whole job on the ordinary brightfield IHC that every pathology lab already runs.** Point it at the images a lab already produces, and it detects cells, quantifies markers, runs spatial statistics, certifies its own assumptions, and writes a report in which every result is backed by an explicit validity check.

The trust isn't a disclaimer bolted on at the end — it's built into the workflow.

---

## Inside the platform

A single guided pipeline replaces a folder of disconnected tools — from a raw slide to a defensible, validation-aware report.

### 🗂️ Batch processing

Point it at a folder and it processes an entire experiment automatically — every slide segmented, quantified, and exported, with no manual transfers or per-image babysitting. **This is the difference between a script and a platform.**

<p align="center"><img src="images/batch-segmentation.png" alt="Batch segmentation overlay" width="46%"></p>

### 🔬 Segmentation & quantification

Every nucleus is detected on commodity brightfield, and DAB optical density is measured per cell to count marker-positive cells — reported with overlays you can inspect down to the individual cell.

<p align="center"><img src="images/single-analysis.png" alt="Segmentation and DAB-positive detection" width="92%"></p>

### 🧭 Spatial analysis

For two markers across serial sections, the platform measures how their cell populations sit in space — but only after the alignment between sections is **certified**, and only inside the region that can be trusted. Density overlays make the relationship visible at a glance.

<p align="center"><img src="images/spatial-density.png" alt="Cross-type density overlay" width="56%"></p>

### ✅ Validation & trust

The platform is engineered to **say no.** On a real certified pair, a naïve test reported a strong association (p = 0.001); the calibrated test returned p = 0.32 and flagged it as a shared-tissue artifact. **Same data — the design is what stopped the wrong answer from being believed.**

<p align="center"><img src="images/artifact-caught.png" alt="Calibrated null refusing a false positive" width="86%"></p>

### 🧬 Same-section co-expression

When two stains are imaged on the *same* physical section, the exact same cells are reused to call true single-cell co-expression — here, CD8 versus FOXP3.

<p align="center"><img src="images/restained-coexpression.png" alt="Same-section co-expression overlay" width="46%"></p>

### 📄 Reporting

Every run produces clean, reproducible outputs — overlays, tables, and a validation-aware summary that separates what is supported from what is not.

---

## Why it matters

Advanced spatial analysis shouldn't be the privilege of a handful of well-funded centres. By running on the stains, scanners, and archived slides that pathology labs already have, IHC Analyzer brings trustworthy spatial cancer analysis within reach far more widely — **without ever trading rigor for accessibility.**

---

<p align="center">
  <a href="https://ihc-analysis-interactivedemo.vercel.app"><b>▶&nbsp;&nbsp;Experience the Interactive Demo</b></a>
</p>

<p align="center">
  <sub>IHC Analyzer — automated, validated, reproducible digital pathology. Built and tested against reference implementations and expert-annotated datasets.</sub>
</p>
