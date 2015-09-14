TEX=lualatex
EXAMPLES=fullpredict
EXAMPLES_PDF:=$(addsuffix .pdf, ${EXAMPLES})
EXAMPLES_SVG:=$(addsuffix .svg, ${EXAMPLES})

all: ${EXAMPLES_PDF} ${EXAMPLES_SVG}
%.pdf: %.tex ../pfasst.tex
	${TEX} $<
	# pdfcrop --hires $@ $@
%.svg: %.pdf
	inkscape -l $@ $<

.PHONY: clean
clean:
	rm -f *.aux *.log *.pdf *.svg
