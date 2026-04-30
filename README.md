[README.md](https://github.com/user-attachments/files/27239770/README.md)
# Regulation of Foundational Models and Generative AI: Fundamental Right to Data Protection

**Interactive data visualisation of a KU Leuven Master's thesis in IP & ICT Law**

> *A comparative legal analysis of how the EU (GDPR + AI Act) and China (PIPL + IMGAI + MAIL) govern the use of personal data in large-scale AI systems — and why the fundamental rights framing still matters.*

---

## About

This repository hosts an interactive single-page website that maps and visualises the key arguments, regulatory comparisons, and findings from the thesis:

| | |
|---|---|
| **Title** | Regulation of Foundational Models and Generative AI: Fundamental Right to Data Protection |
| **Author** | Chang-Hua Kao |
| **Promoter** | Ana Maria Corrêa Harcus |
| **Institution** | KU Leuven, Faculty of Law, Campus Brussels |
| **Degree** | Master of Intellectual Property and ICT Law |
| **Academic year** | 2023–2024 |
| **Word count** | 15,126 |

---

## What's Visualised

The site translates six chapters of legal analysis into seven interactive sections:

**1 — Regulatory Landscape Overview**  
Summary statistics and a chapter-by-chapter index: 6 regulatory instruments, 3 analytical dimensions (legality · transparency · safeguards), and 4 AIA risk tiers.

**2 — Dual Regulatory Timeline**  
Side-by-side chronology of EU and Chinese regulatory milestones, from the 1995 EU Data Protection Directive to the 2024 MAIL 2.0 draft — highlighting key instruments with date, jurisdiction badge, and descriptive context.

**3 — Three-Dimension Framework Matrix**  
A cross-tabulation of GDPR, AIA, PIPL, and IMGAI/MAIL against the three core analytical dimensions: lawfulness of processing, transparency obligations, and data subject safeguards.

**4 — GDPR Legal Basis Viability (animated bar chart)**  
All six Article 6(1) GDPR legal bases rated for viability in GPAI model training — from *not applicable* (vital interests, public interest) to *most viable but contested* (legitimate interest). Includes a direct PIPL comparison showing the absence of a legitimate interest basis in Chinese law.

**5 — AIA Risk Pyramid (interactive, expandable)**  
The AI Act's four-tier risk classification — Prohibited, High Risk, Limited Risk, Minimal Risk — plus a dedicated GPAI layer covering the 10²⁵ FLOPs systemic risk threshold and adversarial testing obligations. Each tier expands on click.

**6 — EU vs China Radar Chart**  
A Chart.js radar visualisation comparing the two regulatory regimes across seven structural dimensions: fundamental rights basis, supervisory independence, legal basis breadth, transparency obligations, data subject rights, AI-specific obligations, and judicial review.

**7 — Key Findings**  
Seven conclusion cards drawn directly from the thesis, covering the legitimate interest debate, the "black box" transparency problem, China's consent-only constraint, and the normative argument for fundamental rights framing.

---

## Thesis Structure

```
Chapter 1  Introduction — research questions, methodology
Chapter 2  Data, Models & Generative AI — technical foundations; personal data in the AI lifecycle
Chapter 3  GDPR & Generative AI — legality, transparency, data subject rights under GDPR
Chapter 4  AIA & GPAI — risk-based regulation, GPAI obligations, regulatory sandbox
Chapter 5  Data & AI in China — PIPL, IMGAI, MAIL 2.0 draft
Chapter 6  Comparative Assessment — why fundamental rights framing produces different outcomes
```

---

## Regulatory Instruments Covered

| Instrument | Jurisdiction | Year | Scope |
|---|---|---|---|
| GDPR | EU | 2018 | General data protection |
| AIA (EU AI Act) | EU | 2024 | Risk-based AI regulation |
| PIPL | China | 2021 | Personal information protection |
| IMGAI | China | 2023 | Generative AI interim measures |
| MAIL 2.0 (draft) | China | 2024 | Comprehensive AI law draft |
| CSL / DSL / DSP | China | 2017–2022 | Cybersecurity & deep synthesis |

---

## Key Research Finding

> **The EU's anchoring of data protection in Article 8 of the EU Charter creates a floor that cannot be traded away for AI innovation. China's approach demonstrates that without this constitutional foundation, AI-era data rules tend toward surveillance enablement rather than individual protection.**

The textual similarity between PIPL and GDPR conceals three structural asymmetries that matter enormously for GPAI governance: (1) no independent supervisory authority, (2) no judicial review of constitutionality, and (3) no fundamental right to data protection as a constitutional backstop.

---

## Tech Stack

```
Single-file HTML/CSS/JavaScript — no build step required
├── Chart.js 4.4.1          Radar chart (EU vs China comparison)
├── Google Fonts             Cormorant Garamond · Crimson Pro · JetBrains Mono
├── CSS custom properties    Dark academic theme (navy + gold)
├── Intersection Observer    Scroll-triggered bar chart animations
└── Vanilla JS               Expandable AIA pyramid tiers
```

No frameworks, no dependencies to install, no build pipeline. Drop `index.html` into any static host.

---

## Deploy to GitHub Pages

```bash
# 1. Clone or fork this repository
git clone https://github.com/YOUR_USERNAME/thesis-ai-data-protection

# 2. The site is a single file — index.html
# No installation or build step needed

# 3. Push to GitHub, then enable Pages:
#    Settings → Pages → Branch: main → / (root) → Save

# Your site will be live at:
# https://YOUR_USERNAME.github.io/thesis-ai-data-protection
```

---

## Abbreviations

| Abbreviation | Full name |
|---|---|
| AI | Artificial Intelligence |
| AIA | EU AI Act |
| ARMP | Internet Information Services Algorithmic Recommendation Management Provisions (China) |
| CAC | Cyberspace Administration of China |
| CJEU | Court of Justice of the European Union |
| CSL | Cybersecurity Law (China) |
| DSL | Data Security Law (China) |
| DSP | Deep Synthesis Provisions (China) |
| GDPR | General Data Protection Regulation |
| GPAI | General Purpose Artificial Intelligence |
| IMGAI | Interim Measure on Generative AI (China) |
| LLM | Large Language Model |
| MAIL | Model Artificial Intelligence Law 2.0 draft (China) |
| NPC | National People's Congress (China) |
| PIPL | Personal Information Protection Law (China) |
| TDM | Text and Data Mining |

---

## Academic Context

This visualisation was created for academic reference and public engagement with the thesis research. It does not constitute legal advice. All regulatory summaries are simplified for clarity — the full analysis, citations, and caveats are in the original thesis.

---

*KU Leuven · Faculty of Law · Master of IP & ICT Law · 2023–2024*
