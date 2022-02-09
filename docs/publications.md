# Instructions: Adding Publications
Simply create a `bib` entry to the following file.
<!-- - `_bibliography/dissertations.bib` for dissertations. -->
- `_bibliography/papers.bib` for published papers.
<!-- - `_bibliography/preprints.bib` for preprints. -->

The format is almost identical to a standard `bib` entry, but with a few additional fields:
- `abbr` (required)

- `arxiv` (optional, but encouraged)
- `code` (optional, but encouraged)

- `abstract` (optional)
- `bibtex_show` (optional)
- `html` (optional)
- `pdf` (optional)
- `supp` (optional)
- `blog` (optional)
- `poster` (optional)
- `slides` (optional)
- `talk` (optional)
- `website` (optional)

Here's an example,

```bibtex
@article{Li2021,
  abbr = {CPAM},
  bibtex_show={true},
  author = {Li, Songting and McLaughlin, David W. and Zhou, Douglas},
  doi = {10.1002/cpa.22020},
  issn = {0010-3640},
  journal = {Commun. Pure Appl. Math.},
  month = {aug},
  pages = {cpa.22020},
  title = {{Mathematical Modeling and Analysis of Spatial Neuron Dynamics: Dendritic Integration and Beyond}},
  html = {https://onlinelibrary.wiley.com/doi/10.1002/cpa.22020},
  year = {2021},
  selected={true},
}
```
