# Instructions: Adding Publications

Our publications page is generated automatically from your BibTeX bibliography.
Simply edit `_bibliography/papers.bib`.
<p align="center"><img src="https://raw.githubusercontent.com/alshedivat/al-folio/master/assets/img/publications-screenshot.png" width=800></p>

Simply create a `bib` entry to the following file.
<!-- - `_bibliography/dissertations.bib` for dissertations. -->
- `_bibliography/papers.bib` for published papers.
<!-- - `_bibliography/preprints.bib` for preprints. -->

The format is almost identical to a standard `bib` entry, but with a few additional fields:
- `abbr` (optional): the abbrivation of journal.

- `bibtex_show` (optional, but encouraged): show the link button of `bib` entry, if true.
- `abstract` (optional, but encouraged): show the link button for abstract.
- `html` (optional, but encouraged): show the link button to redirect to origianl paper website.
- `pdf` (optional, but encouraged): show the link button to redirect to pdf file.
- `selected` (optional): the publication is presented at `about.html` if true.


Here's an example,

```bibtex
@article{Song2021,
  abbr = {Cereb. Cortex},
  bibtex_show={true},
  abstract = {A brain network comprises a substantial amount of short-range connections with an admixture of long-range connections. The portion of long-range connections in brain networks is observed to be quantitatively dissimilar across species. It is hypothesized that the length of connections is constrained by the spatial embedding of brain networks, yet fundamental principles that underlie the wiring length distribution remain unclear. By quantifying the structural diversity of a brain network using Shannon's entropy, here we show that the wiring length distribution across multiple species—including Drosophila, mouse, macaque, human, and C. elegans—follows the maximum entropy principle (MAP) under the constraints of limited wiring material and the spatial locations of brain areas or neurons. In addition, by considering stochastic axonal growth, we propose a network formation process capable of reproducing wiring length distributions of the 5 species, thereby implementing MAP in a biologically plausible manner. We further develop a generative model incorporating MAP, and show that, for the 5 species, the generated network exhibits high similarity to the real network. Our work indicates that the brain connectivity evolves to be structurally diversified by maximizing entropy to support efficient interareal communication, providing a potential organizational principle of brain networks.},
  author = {Song, Yuru and Zhou, Douglas and Li, Songting},
  doi = {10.1093/cercor/bhab110},
  issn = {1047-3211},
  journal = {Cereb. Cortex},
  month = {aug},
  number = {10},
  pages = {4628--4641},
  title = {Maximum Entropy Principle Underlies Wiring Length Distribution in Brain Networks},
  html = {https://academic.oup.com/cercor/article/31/10/4628/6276649},
  volume = {31},
  year = {2021},
  pdf = {Song_Zhou_Li_CerebralCortex_2021.pdf},
}
```

<details><summary>(click to expand) <strong>Author annotation</strong>[Optional]:</summary>

You can add meta-information about your own in `_data/coauthors.yml` and Jekyll will insert links to your webpages automatically.
The coauthor data format in `_data/coauthors.yml` is as follows,
```
"Li":
  - firstname: ["Songting", "S."]
    url: https://ins.sjtu.edu.cn/people/songtingli/

"Zhou":
  - firstname: ["Douglas", "D."]
    url: https://ins.sjtu.edu.cn/people/zdz/ 

"Tian":
  - firstname: ["Zhong-qi K.", "Zhong-qi Kyle", "Z. K.", "Zhong-qi", "Z."]
    url: https://lcns-sjtu.github.io/people/zhongqi_tian/ 

```
If the entry matches one of the combinations of the last names and the first names, it will be highlighted and linked to the url provided.

</details>
