all: JSIMS-template.dvi JSIMS-template.ps JSIMS-template.pdf

JSIMS-template.dvi: JSIMS-template.tex

	platex JSIMS-template.tex
	platex JSIMS-template.tex

JSIMS-template.ps: JSIMS-template.dvi
	pdvips -f JSIMS-template.dvi > JSIMS-template.ps

JSIMS-template.pdf: JSIMS-template.ps
	ps2pdf13 JSIMS-template.ps
