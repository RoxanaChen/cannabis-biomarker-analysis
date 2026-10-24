# Cannabis Biomarkers for DUI Detection Case Study

## Overview
This case study analyzes which cannabis biomarker, in which type of sample, and at what cutoff in which matrix best indicates recent cannabis use in order to help inform DUI law enforcement for cannabis consumption.

## Data
Due to the data being from an ongoing research study, it is restricted and not included in this repository. Study data included:
* Controlled dosing of cannabis, in which participants were given a placebo, low dose, or high dose
* Participants classified as occasional or frequent cannabis users
* Measured compounds of cannabinoids and their metabolites in breath, oral fluid, and whole blood, from before smoking to 300+ minutes after

## Methods
* Combined three datasets and grouped time into windows for cleaner evaluation
* Visualized compound levels over time
* Calculated sensitivity and specificity across different cutoff levels, prioritizing specificity to avoid falsely flagging sober drivers
* **Tools:** tidyverse, janitor, ggplot2, patchwork

## Key Findings
* Recommended a two-step screening for law enforcement: THC in breath as the first roadside test, followed by testing THCCOOH-gluc in blood as confirmation, each at a high cutoff to minimize false positives

## Files
- `cannabis_biomarkers.Rmd`: R Markdown file with the full code and analysis
- `cannabis_biomarkers.html`: rendered report

## Team
Group project by Roxana Chen, Jiayi Xue, Sehee Kim, Jorge Ramos
