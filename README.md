<!--
  IHC Analyzer — public showcase repository.
  Before publishing: replace DEMO_URL and VIDEO_URL below with your live links.
-->

<p align="center">
  <img src="images/hero.png" alt="IHC Analyzer" width="100%">
</p>

<h1 align="center">IHC Analyzer</h1>
<p align="center"><b>A digital-pathology platform for trustworthy spatial analysis of brightfield immunohistochemistry.</b></p>

<p align="center">
  <a href="DEMO_URL"><b>▶  Try the Interactive Demo</b></a>
  &nbsp;·&nbsp;
  <a href="VIDEO_URL">Watch the 2-minute video</a>
</p>

---

## Experience it in two minutes

> **The best way to understand IHC Analyzer is to use it.**
>
> The **[Interactive Demo](DEMO_URL)** walks you through the entire workflow — batch processing, segmentation, quantification, trustworthy spatial analysis, and same-section co-expression — on preloaded example data. No installation, no setup, no uploads.

<p align="center">
  <a href="DEMO_URL"><b>→  Launch the Interactive Demo</b></a>
</p>

---

## What it is

Reading where the immune system sits around a tumour — not just how many cells there are — has become one of the most important tools in cancer research. Today that usually means a six-figure multiplex imaging system, or a fragile stack of scripts that is easy to fool.

**IHC Analyzer is a single, professional platform that does the whole job on the ordinary brightfield IHC that every pathology lab already runs** — and is engineered so it never reports a conclusion it cannot defend. Point it at the images a lab already produces, and it detects cells, quantifies markers, runs spatial statistics, checks its own assumptions, and writes a report in which every result is backed by an explicit validity gate.

The trust isn't a disclaimer bolted on at the end — it's built into the workflow.

---

## The workflow

A single guided pipeline replaces a folder of disconnected tools — from a raw slide to a defensible, validation-aware report.

### 🗂️ Batch processing

Point it at a folder and it processes an entire experiment automatically — every slide segmented, quantified, and exported, with no manual transfers or per-image babysitting. This is the difference between a script and a platform.

<p align="center"><img src="images/batch-segmentation.png" alt="Batch segmentation overlay" width="48%"></p>

### 🔬 Segmentation & quantification

Every nucleus is detected on commodity brightfield, and DAB optical density is measured per cell to count marker-positive cells — reported with overlays you can inspect.

<p align="center"><img src="images/single-analysis.png" alt="Single-image segmentation and DAB-positive detection" width="100%"></p>

### 🧭 Spatial analysis

For two markers across serial sections, the platform measures how their cell populations sit in space — but only after the alignment between sections is **certified**, and only inside the region that can be trusted. Density overlays make the relationship visible.

<p align="center">
  <img src="images/spatial-density.png" alt="Cross-type density overlay" width="58%">
</p>

### ✅ Validation & trust

The platform is built to **say no.** On a real example pair, a naïve test reported a strong association (p = 0.001); the calibrated test returned p = 0.32 and flagged it as a shared-tissue artifact. **Same data — the design is what stopped the wrong answer from being believed.**

<p align="center"><img src="images/artifact-caught.png" alt="Calibrated null refusing a false positive" width="78%"></p>

### 🧬 Same-section co-expression

When two stains are imaged on the *same* physical section, the exact same cells are reused to call true single-cell co-expression — here, CD8 versus FOXP3.

<p align="center"><img src="images/restained-coexpression.png" alt="Same-section co-expression overlay" width="48%"></p>

### 📄 Reporting

Every run produces clean, reproducible outputs — overlays, tables, and a validation-aware summary that separates what is supported from what is not.

---

## Why it matters

Advanced spatial analysis shouldn't be the privilege of a handful of well-funded centres. By running on the stains, scanners, and archived slides that pathology labs already have, IHC Analyzer brings trustworthy spatial analysis within reach far more widely — without ever trading rigor for accessibility.

---

## Try it

| | |
|---|---|
| **▶ Interactive Demo** | [DEMO_URL](DEMO_URL) |
| **🎬 Demo video** | [VIDEO_URL](VIDEO_URL) |

---

<p align="center"><i>IHC Analyzer is a research method-development platform. It is not a deployed clinical diagnostic tool, and the example datasets shown here are used to demonstrate and validate the software, not to make biological claims.</i></p>
