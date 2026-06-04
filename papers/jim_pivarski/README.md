# Local drafting

This directory is set up for the SciPy proceedings submission workflow.

- `main.tex`, `myst.yml`, and `mybib.bib` are the files used by the SciPy build.
- `local.tex` is only for local PDF preview with `pdflatex`; SciPy does not use it.

To build a local preview PDF:

```bash
cd papers/jim_pivarski
pdflatex local.tex
bibtex local
pdflatex local.tex
pdflatex local.tex
```
