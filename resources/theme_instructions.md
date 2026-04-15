# Presentation Theme Instructions

Colour palette for `image-classification-masterclass.qmd` and any future slides.

---

## Colour Reference

| Role | Hex | RGB |
|---|---|---|
| **Slide background** (title slide only) | `#51247a` | (81, 36, 122) |
| **Headings & subheadings** | `#962a8b` | (150, 42, 139) |
| **Tips** (callout-tip) | `#2ea836` | (46, 168, 54) |
| **Warnings** (callout-warning) | `#eb602b` | (235, 96, 43) |
| **Mermaid diagrams** | `#4085c6` | (64, 133, 198) |

---

## Mermaid Diagrams

All mermaid diagrams use the following `%%{init:...}%%` directive at the top of every code block:

```
%%{init: {"theme": "base", "themeVariables": {"primaryColor": "#4085c6", "primaryTextColor": "#ffffff", "primaryBorderColor": "#2d6ba8", "lineColor": "#2d6ba8", "edgeLabelBackground": "#e8f0fa"}}}%%
```

| Variable | Value | Effect |
|---|---|---|
| `primaryColor` | `#4085c6` | Node fill colour |
| `primaryTextColor` | `#ffffff` | Text inside nodes |
| `primaryBorderColor` | `#2d6ba8` | Node border (darker blue) |
| `lineColor` | `#2d6ba8` | Arrow / edge lines |
| `edgeLabelBackground` | `#e8f0fa` | Background behind edge labels |

---

## SCSS Variables (`custom.scss`)

```scss
$uq-purple:    #51247A;   // title slide background, headings
$uq-purple-light: #962a8b; // subheadings (override from UQ brand)
$uq-green:     #2EA836;   // tips (callout-tip)
$uq-orange:    #EB602B;   // warnings (callout-warning)
$uq-blue-alt:  #4085C6;   // mermaid diagrams
```

---

## Usage Notes

- The **title slide** background colour (`#51247a`) is set via `data-background-color` in the slide YAML — it applies to that one slide only.
- **Headings** use `$uq-purple` by default in `custom.scss`; update `$presentation-heading-color` if you want to shift to `#962a8b` for all headings.
- **Tips** and **Warnings** map directly to Quarto's `.callout-tip` and `.callout-warning` classes, styled in `custom.scss`.
- Every new mermaid block must include the `%%{init:...}%%` directive on the first line to inherit the correct colour scheme.
