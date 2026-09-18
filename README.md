# Small-sample multivariate marine-field reconstruction

This repository contains the manuscript source, figures, baseline materials, and
reproducibility records for the small-sample multivariate marine environmental
field reconstruction study.

## Contents

- `marine_reconstruction_paper.tex`: editable IEEE LaTeX manuscript.
- `figures/`: figures referenced by the manuscript.
- `figures_original/`: archived original figures before figure substitutions.
- `reproducibility_bundle/`: data, baseline source code, scripts, and recorded metrics.
- `build/marine_reconstruction_paper_compact.pdf`: five-page compiled manuscript.

## Reproduction notes

The experiment uses nine marine regions, seven variables, chronological 14/5/5
train/validation/test splits, shared mask seeds, and original-unit metrics. See
the README and manifest inside `reproducibility_bundle/` for data hashes and
method-specific details. Large generated files and nested repository metadata
are excluded by `.gitignore`.

## Citation

Please cite the accompanying manuscript after publication. This repository is
intended to preserve the exact source, figures, and experiment records used for
the submitted version.
