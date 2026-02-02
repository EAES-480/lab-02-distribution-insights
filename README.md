# Lab 02 — Building Intuition and Accurately Describing Data Distributions

**EAES 480: Modern Statistics in Earth & Environmental Science**  
University of Illinois Chicago  
Instructor: Dr. Gavin McNicol  

---

DATASET INFO: https://doi.org/10.2737/ WO-GTR-104.
US Forest Inventory Analysis Methdology

EXAMPLE PAPER USING THIS DATASET: https://paperpile.com/shared/soZJjvhA4S3mZrbo_aOQ7OA
Carter and Buma (2025) Different topographic and climatic contexts associated carbon hotspots in a carbon‐dense ecoregion

## Overview

This lab introduces **distributions as the foundation of statistical thinking** in Earth & Environmental Science.

Rather than focusing on formulas, this assignment emphasizes:
- *seeing* data before summarizing it,
- choosing appropriate visualizations,
- describing distributions using robust statistics, and
- connecting plots to scientific interpretation.

You will work in a structured **R Markdown (`.Rmd`) document** that asks you to:
- complete missing code,
- run and inspect plots,
- and write short interpretation responses throughout.

This lab prepares you for later units on probability, uncertainty, and inference.

---

## Learning Goals

By the end of this lab, you should be able to:

- Visualize continuous data using histograms, density plots, and boxplots  
- Explain how binning and smoothing affect interpretation  
- Describe distributions using center, spread, and quantiles  
- Identify skew, outliers, and multimodality  
- Connect distributional features to environmental processes  
- Produce a **fully reproducible** R Markdown analysis

---

## What You’ll Do

In the provided R Markdown template, you will:

- Load and inspect an environmental dataset
- Complete **guided code chunks** (marked with TODOs or blanks)
- Generate:
  - histograms and density plots,
  - grouped comparisons,
  - boxplots and quantile summaries
- Answer short **interpretation prompts** in complete sentences
- Knit the document to confirm it runs cleanly from top to bottom

This is a **thinking + doing lab**: code and interpretation matter equally.

---

## Repository Contents

- `lab-02-distributions.Rmd`  
  → The lab template you will complete and submit  

- `README.md`  
  → This file  

---

## Instructions

1. **Fork or clone** this repository to your own GitHub account
2. Open `lab-02-distributions.Rmd` in **RStudio**
3. Work through the document **from top to bottom**
4. Fill in missing code **only inside the existing code chunks**
5. Respond to interpretation prompts in plain text (outside code chunks)
6. Knit the document regularly to catch errors early

> ⚠️ Code that runs in the Console but not in the `.Rmd` does not count.

---

## Reproducibility Requirements

Your submission **must**:

- Knit without errors
- Run top-to-bottom in a clean R session
- Include all required libraries in the setup chunk
- Avoid hard-coded local file paths
- Use `na.rm = TRUE` where appropriate

These are not stylistic preferences—they are core scientific skills.

---

## Submission

- Commit and push your completed `.Rmd` file to your GitHub repository
- Submit the **GitHub repository link** on Canvas
- You do **not** need to submit the knitted HTML unless instructed

Your work will be evaluated on:
- correctness of code,
- quality of interpretation,
- and reproducibility.

---

## Collaboration Policy

- You may discuss concepts and strategies with classmates
- You may not copy code verbatim from others
- Code you submit must be written and understood by you

If you worked with someone, acknowledge them in a comment.

---

## Tips for Success

- Knit early and often
- Read error messages carefully—they are usually informative
- If a plot surprises you, *that’s a feature, not a bug*
- Focus on **what the distribution is telling you**, not just “getting the answer”

---

## Why This Matters

In Earth & Environmental Science:
- variability is the signal,
- averages can mislead,
- and assumptions matter.

Everything we do later in EAES 480—probability, uncertainty, confidence intervals, models—rests on understanding distributions.

This lab is where that foundation is built.
