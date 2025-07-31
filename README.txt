
Thesis proposal template

Files:
- main.tex — LaTeX source
- references.bib — BibLaTeX database
- figures/ — put your PNG/PDF figures here; names already referenced in main.tex

To compile on Overleaf:
- Set compiler to "LaTeX -> PDF" with Biber (default on Overleaf).
- Ensure `references.bib` is present.
- Replace author/title; fill in bibliography entries and cite with \parencite{key}.

Switching citation style:
- In `\usepackage[...]{biblatex}` change `style=authoryear` to `style=numeric` (or `nature`, etc.).
