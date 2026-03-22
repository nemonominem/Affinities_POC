# Affinities_POC

About
- Affinities_POC is both a technical proof-of-concept for producing print-ready PDFs from Markdown and a substantive scholarly essay on the question of affinities in human relationships. The main source file, `Affinities_POC_improved.md`, contains a carefully referenced essay (March 2026) that synthesizes behavioral-genetics evidence, social-psychological findings, and normative caveats. The workspace also includes the generated PDF and simple reproduction instructions for macOS.

Purpose
- This repository preserves the essay source and the exported A4 PDF `Affinities_POC_improved.pdf`, and documents how to reproduce the PDF generation.
# Affinities_POC

This project contains the Markdown source, notes, and a short proof-of-concept analysis about affinities between people. Its main purpose is to generate a formatted A4 PDF report from the included Markdown using `pandoc` and a LaTeX engine.

Purpose
- This repository contains the Markdown source used to generate the A4 PDF `Affinities_POC_improved.pdf`.

Prerequisites (macOS)
- `pandoc` (for Markdown → PDF)
- A LaTeX engine (recommended: `xelatex`, part of MacTeX or TinyTeX)
- Optional: `conda`/`pyenv` or a virtualenv named `python_313x` if you want to run under that interpreter

Quick regenerate instructions
1. (Optional) activate your Python environment:

```
conda activate python_313x
# or
pyenv activate python_313x
# or
source .venv/bin/activate
```

2. Convert the Markdown to A4 PDF with 2.5cm margins (uses `xelatex` if available):

```
INPUT="Affinities_POC_improved.md"
OUT="${INPUT%.*}.pdf"
pandoc "$INPUT" -o "$OUT" -V geometry:a4paper -V geometry:margin=2.5cm --pdf-engine=xelatex
```

If `xelatex` is not installed Pandoc will fall back to `pdflatex` if present.

Install prerequisites (homebrew example)

```
brew install pandoc
# Install a LaTeX distribution (MacTeX is large):
brew install --cask mactex
# or install TinyTeX via R: https://yihui.org/tinytex/
```

Notes
- The generated PDF `Affinities_POC_improved.pdf` is placed in the repository root.
- If you want different margins or paper size, change the `geometry` variables passed to `pandoc`.

Questions or changes
- Tell me if you want this README expanded, a license added, or automated scripts/Makefile for regeneration.
