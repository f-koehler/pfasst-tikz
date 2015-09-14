pfasst-tikz
===========

Visualize how the PFASST algorithm works using TikZ. The `math` library of TikZ is used and therefore TikZ >= 3.0.0 is required. TeX Live 2014 or later should fulfill this requirement.

I created an example svg (the original PDF looks nicer though):

![Example of PFASST with 2 steps + 1 fine sweep](http://f-koehler.github.io/pfasst-tikz/pfasst.svg "Example of PFASST with 2 steps + 1 fine sweep")

Requirements:
- `TikZ/PGF` from TeX Live

Requirements for examples:
- `pdf2svg` (for optional svg export)
- `latexmk` from TeX Live
- `pdfcrop` from TeX Live
- `standalone` from TeX Live
