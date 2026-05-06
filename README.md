# Easy Image Classification Masterclass

Author: Sebastian Lopez Marcano [<img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD" width="16">](https://orcid.org/0000-0002-0814-2906)

Organisation: Data Science Collaborative Research Program (DSCRP), The University of Queensland 

----------
This repository contains slides and supporting materials for a **2-hour masterclass** on practical computer vision with Roboflow.

The workshop focuses on clear decision-making for real projects: choosing the right task (classification, detection, segmentation), building reliable datasets, understanding evaluation, and knowing when tools are enough versus when expert help is needed.

## Current Presentation

- Main slide deck: [presentation/image-classification-masterclass.qmd](presentation/image-classification-masterclass.qmd)
- Rendered slides (if generated): [presentation/image-classification-masterclass.html](presentation/image-classification-masterclass.html)
- Custom styling: [presentation/custom.scss](presentation/custom.scss)

## Masterclass Scope

The current deck covers:

1. Computer vision fundamentals
2. Classification vs detection vs segmentation
3. Collecting and labelling data (including Roboflow Universe and assisted labelling)
4. Training, validation and testing
5. Domain shift, transfer learning and foundational models
6. Deployment basics
7. Ensembles
8. AI tools vs expert support (when to use each)
9. Short practical demos (Playground, Notebooks/Colab, Universe)
10. Post-workshop support

## Audience

Suitable for beginners to intermediate users who want a practical, non-theoretical entry point to computer vision workflows.

## Prerequisites

- A laptop with internet access
- A free [Roboflow account](https://app.roboflow.com/)
- Basic familiarity with Python is helpful but not mandatory for the conceptual sections

## Render The Slides

From the repository root:

```bash
quarto render presentation/image-classification-masterclass.qmd
```

For live preview while editing:

```bash
quarto preview presentation/image-classification-masterclass.qmd
```

## Repository Structure

- [presentation/](presentation/) — Quarto source, styles, assets, and rendered slides
- [resources/](resources/) — supporting notes and instructions
