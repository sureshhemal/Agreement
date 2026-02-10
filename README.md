# Agreement — LaTeX Document

A LaTeX template for formal agreements.

## Build

From this directory:

```bash
pdflatex main.tex
```

For a clean build (recommended):

```bash
pdflatex main.tex && pdflatex main.tex
```

## Output

- **main.pdf** — compiled agreement document

## Requirements

- A LaTeX distribution (e.g. [MacTeX](https://www.tug.org/mactex/) on macOS, or TeX Live)

## Customize

Edit `main.tex` to add parties, definitions, terms, and dates. Re-run `pdflatex` to regenerate the PDF.
