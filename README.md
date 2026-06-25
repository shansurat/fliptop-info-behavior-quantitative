# Decoding the Bars: A Quantitative Analysis of the Information Behavior of the FlipTop Battle League Fanbase

## Overview
This repository contains the source code, data, and final PDF manuscript for the thesis project completed in partial fulfillment of the requirements for **LIS 192: Quantitative Research Methods in LIS** at the **University of the Philippines - Diliman**.

### Abstract
Since counter-culture media first transitioned to online platforms, there has been a continuous discussion attached to how audiences process dense, culturally specific information. The explosion of Internet-driven video platforms has only accelerated the discussion. This study was undertaken among the fanbase of the FlipTop Battle League, a highly viewed digital rap battle platform. Sixty purposive respondents were identified for the sample. Chi-square analysis was used to answer the three core research questions regarding the audience's reliance on asynchronous decoding behaviors, the YouTube comment section, and "berrypicking" techniques. Results showed a significant reliance on community-generated metadata in the comment sections, but no significant prevalence of active, multi-tab cross-referencing. Implications for further action include recommendations for the integration of in-platform contextual tools.

> **⚠️ Disclaimer:** *This manuscript and dataset were created as an academic requirement for an undergraduate coursework class (LIS 192). While it has been reviewed and evaluated by a course adviser, it has not undergone formal academic peer review and should not be cited as an authoritative literature source.*

## Author
**Kristian Mark S. Surat**  
*School of Library and Information Studies*  
*University of the Philippines - Diliman*

## Project Structure
- `Surat_LIS192_Thesis.qmd`: The primary Quarto markdown file containing the manuscript text and embedded R code for statistical analysis.
- `Surat_LIS192_Thesis.pdf`: The finalized, compiled thesis document.
- `data.csv`: The anonymized raw survey data used for analysis.
- `references.bib`: The BibTeX file containing all literature citations.
- `apa.csl`: The Citation Style Language file enforcing APA formatting.
- `conceptual-framework.png`: Diagram illustrating the study's conceptual framework.

## Build Instructions
To reproduce the final PDF from the source code, ensure you have the following installed:
1. **R** (with packages: `ggplot2`, `psych`, `dplyr`, `likert`)
2. **Quarto CLI**
3. **LaTeX** (via `tinytex` or standard TeX Live installation, including the `framed` package)

Run the following command in the root directory:
```bash
quarto render Surat_LIS192_Thesis.qmd --to pdf
```
