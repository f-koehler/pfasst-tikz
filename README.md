pfasst-tikz
===========

Visualize how the PFASST algorithm works using TikZ. The `math` library of TikZ is used and therefore TikZ >= 3.0.0. TeX Live 2014 or later should fulfill this requirement.

I created an example svg (the original PDF lookfs nicer though):

![Example of PFASST with 2 steps + 1 fine sweep](https://cdn.rawgit.com/f-koehler/pfasst-tikz/master/pfasst.svg "Example of PFASST with 2 steps + 1 fine sweep")

Requirements:
- `TikZ/PGF` from TeX Live

Requirements for examples:
- `pdf2svg` (for optional svg export)
- `latexmk` from TeX Live
- `pdfcrop` from TeX Live
- `standalone` from TeX Live
